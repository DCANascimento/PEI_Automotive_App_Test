# PEI_Automotive_App_Test

## Report

Here is the tutorial on how to edit and compile the `.tex` file and get the `.pdf` equivalent.

### Windows

1) Install [MiKTeX](https://miktex.org/download) and, during the installation, choose "Install missing packages on-the-fly: **Yes**" and “**Check for updates now**” - this is **important**!

2) In your taskbar, there should be **MiKTeK Console**, click on `Restore` to open it.

3) On the console, go to the `Updates` tab, then, click on `Update now`. You can exit the console after.

4) Now we should install [Strawberry Perl](https://strawberryperl.com/)

5) After installing, if you didn't change the installation directory, it defaults to `C:\Strawberry\perl\bin`. Copy that path, then, search on the Windows search bar for `Editar as variáveis de ambiente do sistema` and click on it. Click on the `Variáveis de ambiente` button. Now select `Path` from the `Variáveis do sistema` area and click on `Editar`. Now click on `Novo` and paste the path you copied before and exit every window by clicking `OK`. 
   
Note: if the path was already there (like me), you don't need to paste it again and can skip this step altogether. Sometimes the installation already takes cares of this step, sometimes it doesn't, so, here it is just in case.

6) In VSCode, please install the extension "**LaTeX Workshop**" by James Yu. After, please restart VSCode.

7) Now, it should compile. Just go into the `main.tex` file and click on the :arrow_forward: button to start the process. In the first time it will take some time, don't worry, just look at the `Build` on the bottom left corner showing the process. After compiling, even though it might say that it ended in error, it will give the `main.pdf` file!

Please, if you get stuck on some of these points, just, read it again and try it again.

Note: now, really, if you get stuck, see [this](https://www.freecodecamp.org/news/how-to-run-latex-projects-locally-for-free-on-windows/).

Other Note: it's normal in LaTeX files to have a lot of errors (kinda like Java files), but Overleaf hides them and doesn't ask the user to fix those smaller things. Now, I don't want our report to have any error, so, after each one of you has LaTeX working and can edit the report, I want these compilation errors to be fixed.

Last Note: if it's not giving the `main.pdf` and, if you open the output terminal in VSCode showing the LaTeX Compiler output and there's nothing, it's probably because it's not recognizing the `MikTeK` packages, so, please, just re-install (uninstall first) `MikTeK` and test if there's any output when runing `pdflatex --version` on the powershell (it should).