# picoCTF2021-General Skills

## Obident cat 
* first download the file named, "flag"
* on the terminal type, "cat flag"
* should return, "picoCTF{s4n1ty_v3r1f13d_b5aeb3dd}"

## Mod 26
* Rot13 aka "Rotate by 13 places" is a subsitution cypher that replaces a letter with a 13th letter after it on the alphabet.
```
ABCDEFGHIJKLM
NOPQRSTUVWXYZ
```
* You can go on "https://rot13.com/" to translate (unless you want to do it by hand)
* should return, "picoCTF{next_time_I'll_try_2_rounds_of_rot13_ZNMldSDw}"

## Wave a flag
* first download the file named "warm"
* on the terminal type, "wget https://mercury.picoctf.net/static/a14be2648c73e3cda5fc8490a2f476af/warm"
* Turn the "warm" file into an executable, "chmod 744 warm" 
* execute "warm", "./warm"
* should return "Hello user! Pass me a -h to learn what I can do!
* on the terminal, "./warm -h"
* should return, "Oh, help? I actully don't do much, but I do have this flag here: picoCTF{b1sc1ts_4nd_gr4vy_755f3544}" 

## Magikarp Ground Mission
* On the terminal SSH into the right place, "ssh ctf-player@venus.picoctf.net -p 49953"
* enter the password, "6d448c9c"
* your terminal should look like, "ctf-player@pico-chall$ "
* if you type, "ls" you should see, "1of3.flag.txt" and "instructions-to2of3.txt"
* the 2nd instruction says to go to the root of all things, on the terminal, "cd /", 
* if you type, "ls" theres many files but you can identify, "2of3.flag.txt" and "instructions-to-3of3.txt"
* the 3rd instructions says to go home, on the terminal type, "cd ~"
* if you type, "ls" you should see, "3of3.flag.txt"
* if you add up all the flags it should read, "picoCTF{xxsh_0ut_0f_\/\/4t3r5190b070}"

## static aint always noise
* first download the file named "static"
* on the terminl, "cat static"
* in the middle of the gibberish, you can find "picoCTF{d15a5m_t34s3r_1e6a7731}"

## Tab, Tab, Attack
* first donwload the file named "Addadshashanammu.zip"
* on the terminal unzip the file "unzip Addadshashanammu.zip"
* FROM NOW ON YOU SHOULD USE THE [TAB] BUTTON TO AUTOCOMPLETE INSTEAD OF TYPING THE GIBBERISH NAME
* on the terminal, "cd (tab)"
* then, "cd (tab)"
* then, "cd (tab)"
* then, "cd (tab)"
* then, "cd (tab)"
* then, "cd (tab)"
* then, "cd (tab)"
* then, "cat (tab)"
* the file might look like gibberish, but in the middle of the gibberish you can find the flag "picoCTF{l335t!_524e3dc4"

## Python Wrangling
* first you should download "ende.py" "flag.txt.en" "pw.txt"
* on the terminal run "wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py"
* if you read the "ende.py" it says to use "-e" "-d" "-h" //probably for "encrypt" "decrypt" "help"
* The description says "Can you run this Python script using this password to get the flag?"
* Copy paste the password from pw.txt
* on the terminal "python ende.py -d flag.txt.en" 
* this will ask you to enter a password, use the one from "pw.txt"
* should return the flag "picoCTF{4p0110_1n_7h3_h0us3_aa821c16}"
