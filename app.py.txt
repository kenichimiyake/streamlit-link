import streamlit as st

st.title("リンクページ")

st.write("外部リンクはこちらです")

# ボタンのリンク（押すと別タブで開く）
st.link_button("Song LLC を開く", "https://song.co.jp/fx/")

# 青い文字のリンク（普通のリンク）
st.markdown("[Song LLC（テキストリンク）](https://song.co.jp/fx/)")
