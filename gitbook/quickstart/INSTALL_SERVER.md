# Install server side

### Step 1: Choose a VPS
* Log in to [Amazon Web Services(AWS)](https://aws.amazon.com/)
* Create an instance
* SSH to your instance

	More details check video below:
	{% video %}https://vimeo.com/304732903{% endvideo %} 


### Step 2: Install environment
Install [dependency](https://hilanderas.github.io/powter-server/en/usage/quickstart/DEPENDENCY.html) for powter-server
{% video %}https://vimeo.com/304732903{% endvideo %} 

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