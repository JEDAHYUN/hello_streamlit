 st.write('Hello world!')
 st.header('st.button')
 if st.button('Say hello'):
 st.write('Why hello there')
 else:
 st.write('Goodbye')
 st.header('st.slider')
 st.subheader('Slider')
 age = st.slider('당신의 나이는?', 0, 130, 25)
 st.write("나는 ", age, '살입니다')
