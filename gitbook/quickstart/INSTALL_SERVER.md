# Install server side

### Step 1: Choose a VPS
We recommend the Amazon Lightsail, Vultr, Linode. The mininal configuration is sufficient. The Bandwidth, Latency, Packet Loss are the primary features you should consider. We prefer amazon Lightsail Singapore and Japan nodes, since the latency is only 49-80ms, while the latency from the same location in Vultr and Linode is 120ms-300ms. Please choose Ubuntu 18.04 server as your operating system.

* Log in to [Amazon Web Services(AWS)](https://aws.amazon.com/)
* Create an instance
* SSH to your instance

More details check video below:

{% video %}https://vimeo.com/319140997{% endvideo %}


### Step 2: Install environment
System utilities, Docker CE, docker-compose need to be installed. Refer to [server dependency installation](https://hilanderas.github.io/powter-server/en/usage/quickstart/DEPENDENCY.html)

More details check video below, click vimeo in the bottom right to zoom out:
{% video %}https://vimeo.com/319144825{% endvideo %}

### Step 3: Install powter-server
* Check WAN of your instance, it is `eth0` for AWS
```bash
ifconfig
```
* Check USER of your instance, it is `ubuntu` for AWS
```bash
echo $USER
``` 
* Install [powter-server](https://hilanderas.github.io/powter-server/en/usage/quickstart/INSTALL.html)
