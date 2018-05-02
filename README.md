# Auto configurator openvpn
Installation
-


### Preparatory actions

##### Create SSH key to log on.
```
$ ssh-keygen
```
##### Import the shsyea repository and go to the location directory.
```
$ git clone https://github.com/exctzo/shsyea.git && cd shsyea
```
	

### Creating a remote server in DigitalOcean

##### Install the runtime package for the Ruby.
```
$ apt install ruby
```
##### Install the DropletKit client.
```
$ gem install droplet_kit
```
##### Run the script to create the server.
```
$ ruby create_droplet.rb
```
##### During the execution of the script, you will need to specify the Personal access tokens (generate on [site DigitalOcean](https://cloud.digitalocean.com/settings/api/tokens))
##### Connect to the server:
```
$ ssh ip_address
```


### Building a openvpnVPN server system ###  