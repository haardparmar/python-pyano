import os, requests, threading
from tkinter import *
from playsound import playsound
def downloadmusics():
    urls=["http://download1080.mediafire.com/08z72b8gumjg/h85v9qqu1gqcpmi/1.wav", "http://download1506.mediafire.com/vzybcxtcydcg/10f6fa4liwxldkt/2.wav", "http://download1641.mediafire.com/sfoa4yj1xdug/n4l6et3ta0fv7g8/3.wav", "http://download1475.mediafire.com/f1mz2nh18iyg/z7w98lxbr036sy8/4.wav", "http://download1491.mediafire.com/b6ma3wjizxmg/76e1xn6fmr6wwhj/5.wav", "http://download854.mediafire.com/84fs88b39prg/m9i5f7vtvzfz7zf/6.wav", "http://download855.mediafire.com/h0w0dcqpup6g/ldr2vr2gj425vdo/7.wav", "http://download1077.mediafire.com/7rpn3yzal9sg/szkjzek8gru738l/8.wav", "http://download1325.mediafire.com/ibvet9mdk3xg/jz52y99oz6v5tcv/9.wav", "http://download855.mediafire.com/ma79q95oolog/ytt651u5723a6b1/10.wav", "http://download1348.mediafire.com/0je79702prug/wpk6i4eq4j9yetz/11.wav", "http://download1652.mediafire.com/nrjgq3xch8og/43ynlvw3ljdjx0u/12.wav"]
    os.system("mkdir pianoAudio")
    counter=1
    for i in urls:
        print(f"downloading file {i}.."
              f"Please wait.")
        wavdata = requests.get(i)
        file = open(f"pianoAudio/{counter}.wav"
                    , "wb")
        file.write(wavdata.content)
        file.close()
        counter+=1
downloadmusics()
def setSoundThread(a):
    playsound(f"pianoAudio/{a}.wav")
def playSound(a):
    threading.Thread(target=setSoundThread,args=(a,)).start()
root = Tk()
Label(root, text="PIANO", font=("Arial", 18, "bold")).grid(row=0, columns=13)
class makeButton:
    def __init__(self, a):
        self.index = a
        if self.index % 2 == 1:
            Button(root, command=lambda :playSound(self.index), height=10,
                   width=3, bg="white").grid(row=1, column=self.index)
        else:
            Button(root, command=lambda: playSound(self.index), height=10,
                   width=3, bg="black").grid(row=1, column=self.index)
for i in range(1, 13):
    makeButton(i)
root.resizable(0,0)
root.title("Piano")
root.mainloop()
