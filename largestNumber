import streamlit as st
def largestNumber (number1, number2, number3):
    return max(number1, number2, number3)

def main():
    st.title ("Largest Number")
    number1=st.number_input("Enter the 1st Number")
    number2=st.number_input("Enter the 2nd Number")
    number3=st.number_input("Enter the 3rd Number")
    
    if st.button("Largest Number is"):
        result=largestNumber(number1, number2, number3)
        st.write("The Largest Number among the given numbers is:", result)
main()
