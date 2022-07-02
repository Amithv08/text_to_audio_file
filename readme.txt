import gtts

from gtts import gTTS

from playsound import playsound

language = 'en'
audio = 'speech.mp3'
user_input = input("Text_Converter> ")
sp = gTTS(text= user_input, lang= language, slow=False)
sp.save(audio)                                                       #To save the audio that we get from user_input 
playsound(audio)



# You need to install the required library if it doesn't exist.
