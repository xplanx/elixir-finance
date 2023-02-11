# Elixir-finance
### elixir.finance Bringing liquidity to the long tail of cryptoassets via the industry's decentralized, algorithmic market making protocol
![image](https://user-images.githubusercontent.com/76862881/218249898-d82f6c84-fbf7-410b-9c41-9ce069a5d59a.png)


Prestart:
Join the Elixr discord here : https://discord.gg/MecwhBMP

U need Ubontu VPS 

### Requirement System
  <table>
    <tr>
      <th>Component
      <th>Specifications
    </tr>
    <tr>
      <td>	OS
      <td> Ubuntu 20.04 
    </tr>
     <tr>
      <td>CPU	
      <td> 1 or2 Cores
    </tr>
    <tr>
      <td>RAM	
      <td> 4 GB
    </tr>
    <tr>
      <td>Storage
      <td> 25GB SSD or NVME
    </tr>
   
  </table>
  
 
  ### Recommendation VPS (crypto payment)
<table>
    <tr>
      <th>Provider
      <th>Link
    </tr>
    <tr>
      <td>PQ HOSTING	
      <td>https://pq.hosting/?from=542984
    </tr>
   
</table>

### 15% offer with this promo code : ``` PQandGO ```

For connecting to Your VPS u can install https://hyper.is its Good Terminal

## Step 2 :
Copy this and paste it into the command line

```
sudo apt-get update
```
```
sudo apt upgrade
```
```
sudo apt-get install \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```
Write `` y `` and `` Enter `` for Confrim progsess

#### Then :
```
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
```
#### Then:
```
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```
#### Then:
```
sudo apt-get update
```
#### Then:
```
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
You’ll need to agree to install it. `` y `` And `` Enter ``

#### Then:
```
sudo docker run hello-world
```
It’ll tell you it couldn't find the image and then find it on Docker. Nice. If this confuses you dont worry
you’ll know for sure if you’ve done everything right from this command:
```
docker ps
```
u can see this?
![image](https://user-images.githubusercontent.com/76862881/218248299-15b99e4a-f220-4886-a4c3-f086b1f1cee9.png)

if yes, Step 1 completed!

## Step 2:
U need Evm Wallet Metamask ( new Accaunt for sec your Fund ): https://metamask.io
Then download a new instance of Metamask
Keep the secret phrase safe (this is NOT the private key).
Keep the EVM address handy (starts with 0x) and get the private key while you’re at it.
Note that the private keys are under the three dots, then click account details, then export Private Keys. 

## Step 3:
Back on Terminal and run:
```
wget https://testnet-1-files.elixir.finance/Dockerfile
```
## Step 4:
Now run the following command :
```
nano Dockerfile
```
Use your keys pasting to put the EVM address and the Private Keys in the right bits!

![image](https://user-images.githubusercontent.com/76862881/218249222-8c643960-413b-4b90-a1b0-55f078625da8.png)

Then press (on windows at least) `` ctrl and x `` , then `` y `` and `` Enter ``

(on mac you may need to just follow the instructions to save the config as I dont know how to `` right click `` or `` CTRL `` on mac).

## Step 6
RUN DOCKER 
```
docker build . -f Dockerfile -t elixir-validator
```
## Step 7
Then run:
```
docker run -d --restart unless-stopped --name ev elixir-validator
```
now u are node :)

U can Search Your Node Here (After Minutes) :
https://metrics.elixir.finance
also search by IP Or wallet Adress

Go to the discord and Whitelist channel
Do the twitter tasks first (retweet, follow, connect).
Then paste in your wallet address from the new metamask into the Submit.
Do the twitter first
The bot gets confused if you do it in the order of the buttons.

# DONE!!!

join to our Telegram Channel For Upcoming Crypto Projects : https://t.me/B_FARS


