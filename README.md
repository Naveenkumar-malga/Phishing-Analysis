
# Phishing Analysis(Home Lab)

## Objective

Practiced investigating emails using headers, URLs and attachments.

### Skills Learned

- Email header analysis(Received headers, SPF, DKIM, DMARC check, Reply to and  Return path)
- URL reputation analysis and sandboxing
- Analyzed attachments using tools.
- Documenting the collected artifacts and information about the investigation

### Tools Used

- Virtual machine - Built a VM to analyze real phishing emails
- MX ToolBox - Analyzed headers using mx toolbox
- Sublime Text - Understandind the headers
- Cyberchef - Decoded the encoded contents like base64, quoted pritable and extracted urls from it
- URLscan.io - Checked the url reputation
- VirusTotal - For IP and URL reputation
- Any Run and Hybrid Analysis - For attachment analysis

## Steps

Analyzed email headers using Sublime text and MX toolbox tools in ubuntu Vm.
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_09_12_2025_10_54_44" src="https://github.com/user-attachments/assets/babf3764-26c4-472c-b152-1deeb0501219" />

<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_10_12_2025_15_47_41" src="https://github.com/user-attachments/assets/75218515-9056-4086-a986-25c14d600c7a" />

Checked the authentications results like SPF, DKIM, DMARC
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_10_12_2025_15_47_25" src="https://github.com/user-attachments/assets/87e4c3aa-6434-4982-b0dd-656243a61d47" />

DNS lookup and IP information about sender address

<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_15_12_2025_19_01_59" src="https://github.com/user-attachments/assets/5c6ad6ef-3775-4ff6-ab87-d8761a2a384b" />


<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_09_12_2025_10_45_51" src="https://github.com/user-attachments/assets/f198b9ee-e8d8-4760-aa42-f6d2cc8c4284" />



Converted the base64 encoded content in to normal html form using Cyberchef
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_10_12_2025_11_47_57" src="https://github.com/user-attachments/assets/84eac0bd-2800-4a85-ad59-dfac3f2f1e9f" />

Extracted the URLs from quoted printable encoded content
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_10_12_2025_15_46_29" src="https://github.com/user-attachments/assets/f75d4da5-3b75-4702-ba23-4c5dc1ccd46c" />


Url reutation in url void
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_15_12_2025_19_12_21" src="https://github.com/user-attachments/assets/e58f7947-22a3-4506-bb20-308588a118d6" />



Analyzed the file hash reputation in Cisco tallos intelligence
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_10_12_2025_23_00_21" src="https://github.com/user-attachments/assets/9fd77f18-f1a4-44ff-9b57-64e0f4e79a07" />

Attachment analysis in hybrid analysis
<img width="1920" height="1080" alt="VirtualBox_SOClab-Ubuntu_10_12_2025_23_16_26" src="https://github.com/user-attachments/assets/38eed43b-892c-4337-a962-64481920ef8c" />









