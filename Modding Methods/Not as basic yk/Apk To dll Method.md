# This is for if you want to look for the Assembly-CSharp From the apk (Mostly this is for looking for anti-cheats / Kick stuff or application quit)
- Note: This will not teach you how to remove a anti cheat! Go to Anti-cheat Remover File to do that!

**Requirements**

[DnSpy](https://github.com/dnSpy/dnSpy/releases/tag/v6.1.8)
- Either SamBoy's Version or the one that uses samBoys But its a gui (Which is easier i will be covering both!)

[SamBoy's Cpp2IL](https://github.com/SamboyCoding/Cpp2IL)

[Cpp2IL Gui](https://github.com/dxrkalfie/Cpp2IL-Gui/releases/tag/1.0)

# How to Get DLLs From An Apk!
- step 1. Download all the Requirements However you only need one of the Cpp2IL. (the Gui one is much easier)

# Gui way (Skip if you downloaded samBoys Cpp2IL)
- step 2. After Downloading The gui and dnSpy Open the gui.
- step 3. After opening the application, click browse and look for the apk you are trying to get the Assembly-CSharp for.
- step 4. after doing so, click **"Run Cpp2IL"** Which will run the command that you will need to do.
- step 5. Once you have clicked it, It will create a folder called **cpp2il_out** If there is nothing in the file wait! But if there is continue.
- step 6. Open dnSpy, Click **File** then **Open** then find the file that the DLLs Are in. (Or just drag and drop the Assembly-CSharp.dll or Assembly-CSharpBypass.dll)
- step 7. Then go open it up then find the **-** file then look for a script. Then just put it in notepad!

# SamBoy Cpp2Il Way (A Little Bit harder without knowledge)
- step 2. After Downloading The applications you need,
- Step 3. you want to open your command Prompt,
- step 4. Then you want to copy the path where your SamBoy's Cpp2IL is at!
- step 5. you want to do cd (Then Paste your path) (Like mine will be C:\Users\dxrkalfie\Downloads)
- step 6. after going to your path, make sure the exe is called **Cpp2IL.exe**
- step 7. After renaming your file / doing the path as well, you want to Paste this into your command Prompt: **start Cpp2IL.exe --game-path=Put the Game Path Here! --output-as dummydll --output-to cpp2il_out --use-processor attributeinjector --processor-config key=value**
- Step 8. Where it says --game-path=Put the Game Path Here! Put your apk file game path there! Like mine will be --game-path=C:\Users\dxrkalfie\Downloads\Test.apk
- Step 9. After doing so you should see another command Prompt open up with samboy's stuff on it, (If it closes straight away thats not the exe its the apk)! 
- step 10. After it says its done / closes (NOT STRAIGHT AWAY) You should see a file called **cpp2il_out** Which has all the DLLs.
- step 11. Open dnSpy, Click **File** then **Open** then find the file that the DLLs Are in. (Or just drag and drop the Assembly-CSharp.dll or Assembly-CSharpBypass.dll)
- step 12. Then go open it up then find the **-** file then look for a script. Then just put it in notepad!

## Thats it really, Love you guys ❤️

- Discord: dxrkalfie if you need any help or anything!



