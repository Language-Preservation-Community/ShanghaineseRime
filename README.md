# ShanghaineseRime
An IME for Shanghainese, using Edkins romanisation.

Instructions for Shanghainese Input
1. Download Rime input from https://rime.im/download/ and install by going into the folder in C:\Program Files (x86)\Rime and clicking on WeaselSetup.exe.
2. Download Edkins Input from this repo. (just the .dict file and the .schema file will do)
3. If you are unsure how to download from github, just click on the button code and you will see a button called download Zip. Press on that and you will be able to download
4. Navigate to the Rime inputs folder: C:\Users\[name]\AppData\Roaming\Rime 
5. Open the extracted Edkins file and drag the files
edkins.dict.yaml
edkins.schema.yaml
into the Rime inputs folder and it should look something like this:

5. Open default.custom.yaml file using notepad and type in  - {schema: edkins} under the schema_list and hit save.

6. Then go to the language input method bar on the bottom left of the windows screen and right click on the Gray 中 (or Red A) button; and click on the 重新部署 (R) to redeploy the input.

7. You should be good to go. To type in Shanghainese, switch to the Rime keyboard -> type ctrl + ~ and choose 上海閑話



How to use:<br>

IF YOU HAVEN'T ALREADY INSTALLED RIME:<br>
See Instructions for RIME installation.pdf

1. Afterwards, download ZIP and only extract the dict.yaml and the schema.yaml files to the Rime folder in the Roaming directory.
2. Modify the default.custom.yaml file to include this IME by adding the line `- {schema: edkins}` to it.
3. Re-deploy.

If you need any further assistance, here's our Discord server: https://discord.gg/2qRymM7KFY. Alternatively, flag issues as usual in the Issues tab.
