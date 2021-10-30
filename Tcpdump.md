# Tcpdump ( dump traffic on a Network )

```-D ``` : List aviable interfaces .

<img width="375" alt="Screen Shot 2021-10-30 at 11 33 39" src="https://user-images.githubusercontent.com/92652606/139527815-42850744-f8ff-4b49-a20b-4d9eaa6ce772.png">

```-i interface``` : chose the interface you want to sniff traffic on .

<img width="814" alt="Screen Shot 2021-10-30 at 11 35 46" src="https://user-images.githubusercontent.com/92652606/139527856-4eb3034c-0d9d-4255-b52a-901ea3ebb611.png">

```-w file ``` : write the output to a file.

<img width="678" alt="Screen Shot 2021-10-30 at 11 38 21" src="https://user-images.githubusercontent.com/92652606/139527912-43252afb-527c-4e40-be24-133c8dc2e618.png">

```-r file ```: to read  traffic from a pcap files .

<img width="907" alt="Screen Shot 2021-10-30 at 11 40 26" src="https://user-images.githubusercontent.com/92652606/139527989-354a2396-7382-4d35-a3e5-5fae9ff0ed9f.png">

```-v ```: verbose mode .

```host ip``` : specify the host.

<img width="980" alt="Screen Shot 2021-10-30 at 11 44 03" src="https://user-images.githubusercontent.com/92652606/139528115-34e33997-2bf5-4bf1-9322-2e7c570ed5aa.png">


```port number ```: capture a traffic on a specific port.

<img width="1432" alt="Screen Shot 2021-10-30 at 11 46 44" src="https://user-images.githubusercontent.com/92652606/139528183-10285bf7-d599-48dd-b01f-9dd94f5c00dc.png">

```src ip  ``` : source ip.

```dst ip ``` : destination ip .

``` and , or ``` : is used to combien filters together .

``` -n ```: Display packets with IP address instead of DNS names.

<img width="1432" alt="Screen Shot 2021-10-30 at 11 53 52" src="https://user-images.githubusercontent.com/92652606/139528354-80e41b3b-7817-4c43-8114-d7e0eb9a65f8.png">

```-c N ```: how many packet to capture -c 10.

```-A ```: display packets ASCI.

```-X ```: Display packets ascii and hex.

``` net 192.168.1.0/24 ```:  to capture traffic on the whole subnet.

<img width="1438" alt="Screen Shot 2021-10-30 at 11 58 06" src="https://user-images.githubusercontent.com/92652606/139528464-29048a97-8564-49c5-ba5e-31027f1df15b.png">

```Specify protocol type ``` : tcp , udp , arp , icmp , icmp6 ......

<img width="856" alt="Screen Shot 2021-10-30 at 12 01 57" src="https://user-images.githubusercontent.com/92652606/139528556-00e6b3d0-551e-4a7a-84e1-6d808f2e82c8.png">

[ More info about TCPDUMP Here ](https://danielmiessler.com/study/tcpdump/)
[








