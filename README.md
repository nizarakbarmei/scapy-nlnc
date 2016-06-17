## scapy-nlnc  
Hei, yuk kita mulai pake scapy.  
Apa itu scapy?  
Jadi scapy itu suatu tool untuk membantu kita ngirim paket dari suatu protokol ke ip lain, memalsuin ip pengirim dari paket, menguntit trafik orang lain di jaringan dengan lebih mudah dan tentunya lebih terasa seninya daripada pake tool kayak wireshark.   
Sebelumnya untuk memakai tool ini setidaknya kalian sudah install python. Kalo di laptopku aku pake  

**Python 2.7.11+**   
Langsung aja, cara installnya pertama kamu download  	scapy-2.3.1.zip di repositori ini. Lalu buka terminal dan ketikkan perintah ini:
**sudo su**    
(lalu masukkan password kalian)    
**unzip scapy-2.3.1.zip**    

**cp scapy-2.3.1 /tmp; cd /tmp**      
**python setup.py install**      
(tungu sampai instalasi selesai)      
Lalu install paket lain yang dibutuhkan (khususnya di os yang basisnya debian atau ubuntu):
sudo apt-get install tcpdump graphviz imagemagick python-gnuplot python-crypto python-pyx
Untuk kegunaan paket di atas saya belum tau karena belum mencobanya. Untuk tutorialnya scapyguide1.pdf, mudah dipahami dan lebih fokus ke "learning by doing", dan untuk dokumentasinya scapydoc.pdf.  
Thanks.  
By nizarakbarmeilani  
Untuk lengkapnya, kalian bisa coba baca-baca di [webnya scapy](http://www.secdev.org/projects/scapy/)  
Oh ya ada lagi, ini dari si ari [tutorial yang patut dibaca](http://ezine.echo.or.id/ezine19/e19.009.txt)
`
