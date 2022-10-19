# Transfer_File_DriveGoogle
Download file from website into google Drive
1. Isntall cliget addon on FirFox
2. <a href="https://colab.research.google.com/" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
3. + Code
4. Paste this code to mount GDrive
-   ```console  

    from google.colab import drive
    drive.mount('/content/drive')
    
    ```
6. + Code
-   ```console  

    import os
    os.chdir("/content/drive/My Drive")
    !wget -c "ulr link" --no-check-certificate
    ```
8. "/content/drive/My Drive" the location of file will you put
9. "ulr link" the link of file will you download you can get it with cliget addon after you klick download on the site
Alternatif Link with code <a href="https://colab.research.google.com/drive/1YD_o2k9LaXdCe8vgXGBcyiQpz7r5JaXm?usp=sharing" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
