import tkinter as tk

WindGUI = tk.Tk()
WindGUI.geometry("400x480")
WindGUI.title("Create MP4 PLAYLIST")

AddLblGUI = tk.Label(WindGUI, text="Enter \n MP4 number : ", font=("roboto", 10))
AddLblGUI.place(x=46, y=15)

InptTxtGUI = tk.Entry(WindGUI, width=33)
InptTxtGUI.place(x=140, y=31)

AddBtnGUI = tk.Button(WindGUI, text="Reset to \n Playlist", height= 2, width=10, command="")
AddBtnGUI.place(x=265, y=70)

RstBtnGUI = tk.Button(WindGUI, text="Play \n Playlist", height= 2, width=10, command="")
RstBtnGUI.place(x=165, y=70)

PlyBtnGUI = tk.Button(WindGUI, text="Add \n Playlist", height= 2, width=10, command="")
PlyBtnGUI.place(x=65, y=70)

LstTxtGUI = tk.Text(WindGUI, width=42, height= 18, state= "disabled")
LstTxtGUI.place(x=30, y=120)

PlayedLblGUI = tk.Label(WindGUI, text="Played = x times", font=("roboto", 13))
PlayedLblGUI.place(x=210, y=425)

WindGUI.mainloop()
