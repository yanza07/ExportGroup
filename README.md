# ExportGroup

 ## Description
Corel Macro for batch export
</br> the main idea is export each selected object / group into separate JPGE file
</br> just like [inkscape](https://inkscape.org/) batch export

## Instalation
1. Download or clone this repository
2. open script docker in corel by presing `alt + shift + F11`
3. on script docker click load button
</br> ![load](https://user-images.githubusercontent.com/22528260/156512626-ddfcd32c-9d5e-4cf4-bd47-2a5f860c7d33.jpg)
4. then select `exportGroup.gms` file that you have downloaded / cloned before

## How To Use
1. [install the script](README.md/#Instalation)
2. make sure every object / group you want to export is selected
3. then in the srcipt docker you can easily run the macro file 
    - if you have `simple mode` activated it will look like this 
</br> ![main   simplifed ](https://user-images.githubusercontent.com/22528260/156516695-ecffb51f-220c-4f22-9f62-62ec6e18893d.jpg)
    - if `simple mode` is not activated it will look like this
</br> ![main](https://user-images.githubusercontent.com/22528260/156517092-b6dc7a1f-f21b-43a5-b8de-040d6488cac9.jpg)
4. after the dialog box is coming up set the name and location then click export
5. after export is complete there is another dialog box to open the exported file location
    - click `yes` to open
    - click `no` to close

## Additional Information
- i recommend to bind this script into shortcut (i.e `ctrl + shift + w`) so you dont have to open script docker each time you want to batch export
- by default the exported file will be saved in the `export` folder which is located the same as the file, so before using this macro make sure that you already save the file and create the `export` folder otherwise it will not export anything. But you can change the export location after the export dialog box appears
- exported file will save into JPG file with RGB color mode **(additional information about the export preset will added soon)**
- each exported file will be named sequentially, with the format `file_name [ x ] .jpg` where x is a sequence of numbers starting from 1
- the exported file will automatically replace the  existing file with the same name without any warning
- before being released on github it is my personal tool feel free to personalize with your workflow after you download the file

## Contribution 
any contribution is highly appreciated as long as it doesn't stray far from the main idea, Hopefully in the future it can be useful for the design community in general and the CorelDraw community
</br> In the future I hope I can continue this project, and make some additional features including:
  - export to another file type
  - show how much object selected 
  - option to not replace existing file
