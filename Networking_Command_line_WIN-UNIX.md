# Networking Command line WIN-UNIX

<b> LINUX : </b>

view your computer ip
:

* ``` ifconfig ```

* ```ip a ```

Display routing table
:

* ```route ```:

* ```netstat -r ```:

* ``` ip route ``` :

![Screenshot at 2021-09-21 12-40-56](https://user-images.githubusercontent.com/92652606/139529203-a742d27a-1085-4d4a-ab6b-4cd658c22b96.png)


```ping ``` : sends ICMP to network hosts.
 
```ping -c 3 ``` : sends exactly 3 icmp echo request packets.


![Screenshot at 2021-09-21 12-46-44](https://user-images.githubusercontent.com/92652606/139529243-2b08e184-66d4-448d-b5e6-b0794896498b.png)

``` traceroute ```: see the path your packets take to a remote host.


![Screenshot at 2021-09-21 12-53-11](https://user-images.githubusercontent.com/92652606/139529264-18547639-e49a-44bf-8bf0-37e0e898080d.png)

```host ```: find ip address behind a domain name.

![Screenshot at 2021-09-21 12-57-15](https://user-images.githubusercontent.com/92652606/139529283-ab22efa3-50c1-488c-baa1-44f69b8f31f8.png)

```lsof -i ``` :  list all programs currently using or listeninig to ports.

```lsof -n ``` : disable name resolution.

```lsof -n -i:443 ``` :  looking for a specific port .

```lsof -n iUDP:53 ```: look for udp protcol on port 53.

<b> WINDOWS : </b1>

view your computer ip:

* ``` ipconfig /all :``` /all for more details .

Display routing table
:

```route print : ```

<img width="604" alt="Screen Shot 2021-10-30 at 12 35 57" src="https://user-images.githubusercontent.com/92652606/139529446-7fdc20e0-ea14-4045-8f4f-df2e1be95835.png">


```ping ``` : sends ICMP to network hosts.

```-n number ``` : the same as -c on linux 

<img width="518" alt="Screen Shot 2021-10-30 at 12 37 51" src="https://user-images.githubusercontent.com/92652606/139529510-9a18fcb4-5a7c-49a0-9388-9f904644687f.png">

``` tracert ```:  see the path your packets take to a remote host works the same as traceroute on Linux .


<img width="579" alt="Screen Shot 2021-10-30 at 12 39 46" src="https://user-images.githubusercontent.com/92652606/139529574-2a372094-70d8-4273-8dbe-1b43af9b8eb2.png">

```nslookup```: works the same as ```host```on linux .

<img width="537" alt="Screen Shot 2021-10-30 at 12 42 41" src="https://user-images.githubusercontent.com/92652606/139529677-48a1e0ad-0aa3-471a-9683-7e6099b60197.png">
















