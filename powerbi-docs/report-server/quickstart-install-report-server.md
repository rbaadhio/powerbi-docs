---
title: 'Quickstart: Install Power BI Report Server'
description: Installing Power BI Reports Server itself is very quick. From downloading, to installing and configuring, you should be up and running within a few minutes.
services: powerbi
documentationcenter: ''
author: maggiesMSFT
manager: kfile
backup: ''
editor: ''
tags: ''
qualityfocus: no
qualitydate: ''

ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 03/19/2018
ms.author: maggies

---
# Quickstart: Install Power BI Report Server
Installing Power BI Report Server itself is very quick. From downloading, to installing and configuring, you should be up and running within a few minutes.

This is a quick look at how to install a report server if you just want to get up and running with a new server. For more detailed information on installing a report server, see [Install Power BI Report Server](install-report-server.md).

## Video: Install Power BI Report Server

<iframe width="640" height="360" src="https://www.youtube.com/embed/zacaEb9A4F0?showinfo=0" frameborder="0" allowfullscreen></iframe>

## Before you begin
Before you install Power BI Report Server, we recommend you review the [Hardware and Software Requirements for installing Power BI Report Server](system-requirements.md).

## Step 1: Download

To download Power BI Report Server and Power BI Desktop optimized for Power BI Report Server, go to [On-premises reporting with Power BI Report Server](https://powerbi.microsoft.com/report-server/), and select **Download free trial**.

Follow the instructions to download the installation files locally for Power BI Report Server. 

![Download Power BI Report Server](media/quickstart-install-report-server/download-pbireportserver.png)

## Step 2: Run installer
Run the PowerBIReportServer.exe file that you downloaded and step through the installation screens. You will have the opportunity to select the the installation path as well as select the edition you want to install. You can choose between an evaluation that expires within 180 days, a developer edition or to provide a product key.

![Install Power BI Report Server](media/quickstart-install-report-server/pbireportserver-install.png)

## Step 3: Configure the server
After you are done installing, you will run the configuration manager to finish setting up your server. You will need to create a ReportServer catalog database as well as confirm the web portal and web service URLs.

![Configure Power BI Report Server](media/quickstart-install-report-server/pbireportserver-configure.png)

## Step 4: Browse to web portal
Now that you are configured, you should be able to open a browser to the web portal of your server. By default, this will be `http://localhost/reports`. You will also be able to browse using the machine name instead of using localhost by default, assuming you are not being blocked by any type of firewall.

![Power BI Report Server web portal](media/quickstart-install-report-server/web-portal.png)

## Next steps
[Administrator handbook](admin-handbook-overview.md)  
[How to find your report server product key](find-product-key.md)  
[Install Power BI Report Server](install-report-server.md)  
[Install Power BI Desktop optimized for Power BI Report Server](install-powerbi-desktop.md)  
[Browser support for Power BI Report Server](browser-support.md)

More questions? [Try asking the Power BI Community](https://community.powerbi.com/)

