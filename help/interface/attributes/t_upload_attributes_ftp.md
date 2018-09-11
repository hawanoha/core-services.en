---
description: If you do not upload using drag-and-drop, you can upload customer attribute data via FTP to the Experience Cloud.
keywords: customer attributes;core services
seo-description: If you do not upload using drag-and-drop, you can upload customer attribute data via FTP to the Experience Cloud.
seo-title: Optional - Upload the data file via FTP
solution: Experience Cloud
title: Optional - Upload the data file via FTP
uuid: 07ca9bdf-effa-4e29-881b-42ffd79e23b2
index: y
internal: n
snippet: y
translate: y
---

# Optional - Upload the data file via FTP

If you do not upload using drag-and-drop, you can upload customer attribute data via FTP to the Experience Cloud.

You can upload the data after you create a customer attribute source and an FTP account in the Experience Cloud. You create one FTP account per attribute source. The uploaded files are stored in the root folder of that account. The data must be in [!DNL .csv] format, with a second [!DNL .fin] file to indicate the upload is complete. 

>[!IMPORTANT]
>
>Review [Data file requirements for uploading customer attributes](../attributes/crs_data_file.md#concept_DE908F362DF24172BFEF48E1797DAF19) before uploading the file. 


File uploads to the customer attributes FTP site can be done via FTP or SFTP. 

* You need a client that supports SFTP connections.* You can connect with SFTP using either username/password or using no password, as described [here](https://marketing.adobe.com/resources/help/en_US/whitepapers/ftp/?f=ftp_sftp_cert_auth).



**To upload the data file via FTP** 

1. [Create a customer attribute source and upload the data file...](../attributes/t_crs_usecase.md#task_BCC327B2A0EF4A1BBB2934013AB92B78).

<<<<<<< HEAD
   Ensure that you are logged in to your FTP site at [!DNL ftp.adobe.com/<sftpname>]. 

1. Click **[!UICONTROL Actions]** > **[!UICONTROL File Upload]**.
=======
   Ensure that you are logged in to your FTP site at [!DNL  ftp.adobe.com/<sftpname>]. 
>>>>>>> f4f15dbf132bb389d09b8cd384328a2c98097f4a

1. Upload a [!DNL .fin] file, so that your file can be retrieved.

   The file type [!DNL .fin] is user-created and signals that the upload is finished. It can be a blank notepad file. For example, if you upload [!DNL crs123.csv], you also upload [!DNL crs123.fin]. 

   If the upload is successful, both files are moved to a folder called **processed**. 

<<<<<<< HEAD

       See [Data file requirements for uploading customer attributes](../attributes/crs_data_file.md#concept_DE908F362DF24172BFEF48E1797DAF19) for important information about file names and structure. 
=======
   See [Data file requirements for uploading customer attributes](../attributes/crs_data_file.md#concept_DE908F362DF24172BFEF48E1797DAF19) for important information about file names and structure. 
>>>>>>> f4f15dbf132bb389d09b8cd384328a2c98097f4a