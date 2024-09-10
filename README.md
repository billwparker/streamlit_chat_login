# streamlit_chat_login


pip install streamlit
pip install groq
pip install openai

streamlit run Home.py

Create a .streamlit folder with a file called secrets.toml. Put in this file these two lines plus the passwords section:

open_api_key = 'Your openai api key'<br>
groq_key = 'You groq api key'

[passwords]
"user email" = "user password"
