# Install server side

### Step 1: Choose a VPS
We recommend the [Amazon Lightsail](https://lightsail.aws.amazon.com), [Vultr](https://www.vultr.com/), [Linode](https://www.linode.com/). The mininal configuration is sufficient. The Bandwidth, Latency, Packet Loss are the primary features you should consider. We prefer Amazon Lightsail Singapore and Japan nodes, since the latency is only 49-80ms, while the latency from the same location in Vultr and Linode is 120ms-300ms. Please choose Ubuntu 18.04 server as your operating system. 


|          Features                   | AWS Lightsail                                      | Linode                           | Vultr                                                |
|-------------------------------------|----------------------------------------------------|----------------------------------|------------------------------------------------------|
| Lowest Price per month              | $3.5                                               | $5                               | $2.5                                                 |
| Stability                           |                                                    |                                  |                                                      |
| ping rtt avg<br>(source: domestic)  | 47.956ms(Tokyo)<br>74.961ms(Singapore)             | 117.675ms(Tokyo)                 | 95.156ms(Tokyo)<br>220.360ms(Frankfurt)              |
| Memory Processor Storage            | 512MB Memory<br>1 vCPU<br>20GB SSD<br>1TB Transfer | 1GB Memory<br>1 CPU<br>25GB Disk | 512MB Memory<br>1 CPU<br>20GB SSD<br>500GB Bandwidth |

Take [Amazon Lightsail](https://lightsail.aws.amazon.com) as an example.
* Log in to [Amazon Lightsail Services(AWS)](https://lightsail.aws.amazon.com)
* Create an instance
* SSH to your instance

More details check video below:
<iframe frameborder="0" width="100%" height="450" src="https://www.dailymotion.com/embed/video/x7490i0" allowfullscreen allow="autoplay"></iframe>
Music by [Svyat Ilin](https://icons8.com/music/author/svyat-ilin) from [Fugue](https://icons8.com/music)

### Step 2: Install environment
Ubuntu system utilities, `Docker CE`, `docker-compose` need to be installed. Refer to [server dependency installation](https://hilanderas.github.io/powter-server/en/usage/quickstart/DEPENDENCY.html)

More details check video below, click vimeo in the bottom right to zoom out.
<iframe frameborder="0" width="100%" height="450" src="https://www.dailymotion.com/embed/video/x74pxft" allowfullscreen allow="autoplay"></iframe>
Music by [Svyat Ilin](https://icons8.com/music/author/svyat-ilin) from [Fugue](https://icons8.com/music)

### Step 3: Install powter-server
* Check `WAN interface` of your instance, it is `eth0` for `AWS`.
```bash
ifconfig
```
* Check `USER` of your instance, it is `ubuntu` for `AWS`.
```bash
echo $USER
``` 
* Install [powter-server](https://hilanderas.github.io/powter-server/en/usage/quickstart/INSTALL.html). You will need the `USER` and `WAN interface` above during configuration.
