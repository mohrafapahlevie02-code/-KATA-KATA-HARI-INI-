import streamlit as st
import random
import datetime

st.title("💡 Motivasi Harian")

motivasi = [
    "Tetap semangat, gagal sekali bukan berarti gagal selamanya! 💪",
    "Ingat, usaha kecil setiap hari akan jadi hasil besar nanti. 🌟",
    "Jangan takut mencoba, gagal itu bagian dari belajar. 🚀",
    "Fokus ke proses, hasil akan ikut sendiri. 🎯",
    "Kamu lebih kuat daripada yang kamu kira! 🔥",
    "Satu langkah kecil lebih baik daripada tidak sama sekali. 👣",
    "Jangan bandingin dirimu dengan orang lain, bandingin dengan dirimu kemarin. 🌱"
]

today = datetime.date.today()
pesan = random.choice(motivasi)

st.write(f"📅 Hari ini: **{today}**")
st.success(f"💡 Motivasi Harian: {pesan}")
