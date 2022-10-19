# Transfer_Files_to_GDrive_from_any_site
Download file from website into google Drive
1. Isntall cliget addon on FirFox
2. <a href="https://colab.research.google.com/github/Fhyrhosh/Transfer_File_to_GDrive/blob/main/Download_to_gdrive.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
3. Code to mount GDrive
-   ```console  

    from google.colab import drive
    drive.mount('/content/drive')
    
    ```
4. Code to download
-   ```console  

    import os
    os.chdir("/content/drive/My Drive")
    !wget -c "ulr link" --no-check-certificate
    ```
5. "/content/drive/My Drive" the location of file will you put
6. "ulr link" the link of file will you download you can get it with cliget addon after you klick download on the site
 <br>Alternatif Link with code <a href="https://colab.research.google.com/drive/1YD_o2k9LaXdCe8vgXGBcyiQpz7r5JaXm?usp=sharing" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
