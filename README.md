Elastic Stack: Used as SIEM Solution.
originally used to store, search and visualize large data.
Organizations use it for application monitoring, and now is used at security operations. 

Contains: Elastic Search, LogStash, Beats and Kabana.
Elastic Search for indexing and searching,Logstash does data processing. LogStash inputs user provided data and it filters and normalizes the data and finally outputs the data to kibaba for visualization or elastic search database

The Beats are ships that transfers data from Endpoints to elastic search, beats are data collectors only.

Beats(Collect Data such as Windows logs and Network Packers) ->  LogStash collects data from beats and normalizes and stores them in value pair in the elastic search database -> Elastic Search is the database that has all the normalized data -> Kibana is a visualization tool for data in Elastic Search




<img width="1040" height="413" alt="image" src="https://github.com/user-attachments/assets/a046a213-ff14-4951-9fd1-ead1bcbeba2c" />




<img width="1019" height="351" alt="image" src="https://github.com/user-attachments/assets/5199ed4c-755e-4cb6-aae0-5357cbff8d2b" />

<img width="1735" height="795" alt="image" src="https://github.com/user-attachments/assets/1ee89bbd-f92a-4500-b888-6d2970678dc1" />


<img width="1041" height="504" alt="Screenshot 2026-01-09 134529" src="https://github.com/user-attachments/assets/fab1febf-d0e1-4112-b625-0d4611371109" />


<img width="855" height="648" alt="Screenshot 2026-01-09 134621" src="https://github.com/user-attachments/assets/f380c866-0074-4aea-b327-fef6f914c48e" />


<img width="1655" height="647" alt="Screenshot 2026-01-09 134642" src="https://github.com/user-attachments/assets/cbd54808-7ae9-4948-acee-131882c103f7" />


<img width="270" height="667" alt="Screenshot 2026-01-09 134652" src="https://github.com/user-attachments/assets/be1cfed3-6de3-4ac2-b756-71dc6596b776" />

<img width="402" height="442" alt="Screenshot 2026-01-09 134740" src="https://github.com/user-attachments/assets/46441463-1298-4264-9ea0-d74eac718c36" />

<img width="1656" height="622" alt="Screenshot 2026-01-09 134823" src="https://github.com/user-attachments/assets/8ad66cca-3106-4e10-a7ca-f734b8af5779" />

<img width="1665" height="646" alt="Screenshot 2026-01-09 134845" src="https://github.com/user-attachments/assets/c4fc0e3a-e659-42e9-b3e5-ade0dbf8046e" />

<img width="1658" height="646" alt="Screenshot 2026-01-09 135316" src="https://github.com/user-attachments/assets/ede9f85f-a48f-43d7-8016-0947bc7eaa21" />

Free form search: 

Elastic Stack uses kibana query language (KQL)

<img width="1168" height="273" alt="image" src="https://github.com/user-attachments/assets/9ac861bb-1dac-4343-8637-8bfd6832c0cc" />

Not Operator in Free Form Search:

<img width="588" height="200" alt="image" src="https://github.com/user-attachments/assets/33c16014-a257-4e78-8760-3571a4a41864" />



Field Based Search uses colon and is not a free form search:

<img width="1530" height="648" alt="image" src="https://github.com/user-attachments/assets/b199a44e-5c29-4b4f-9437-419675899aec" />




CREATING a failed filter to see how many ip's failed to connect:
<img width="1069" height="198" alt="image" src="https://github.com/user-attachments/assets/258c7299-6b95-4e64-bfca-34ad04c6473b" />


1. Apply filter:
   
<img width="798" height="356" alt="image" src="https://github.com/user-attachments/assets/c1b31aa9-8326-4fb1-95fe-4dc8b2d9a6de" />

2. Click the field you want to visualize:  I clicked Sourc Ip:
   
<img width="511" height="451" alt="image" src="https://github.com/user-attachments/assets/8038a452-1424-4f21-93d9-f65f706b8e54" />

3. Click as Table to see the data properly.

<img width="1023" height="610" alt="image" src="https://github.com/user-attachments/assets/a6140a7b-b9be-478f-8d6d-11db3df256fa" />

4. We can just drag and drop the username to coorelate and know which user has the failed ip or which user had the failed connection, we can use the vpn_connection or whatever is in the field.

<img width="1192" height="575" alt="image" src="https://github.com/user-attachments/assets/9c68493b-7071-412d-892b-dd6afc3e1107" />

This is what we see with the details of the user and the ip.

<img width="1191" height="359" alt="image" src="https://github.com/user-attachments/assets/56dc0257-2f87-4210-916d-f091e37ba9b2" />


we can also apply other visualizations like bar graph or pie chart.



To add data in the dashboard, we just click dashboard and click add from Library and we have to "SAVE IT"
<img width="1535" height="522" alt="image" src="https://github.com/user-attachments/assets/7fd6d3e7-f156-41e3-8dd1-eec3edde1b5a" />














