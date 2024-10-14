Run SixGPT Miner on VPS
Info
You need to connect your wallet first in SixGPT website
Click on Log In or Sign Up button
Connect your burner wallet
Connect your google drive
Done, For Now
Now you need to request faucet from this website
You can request either moksha or satori faucet
image

To run this miner, you must need to have 6 GB RAM on your VPS or system (Recommended)
If you want to buy any VPS, you can buy from PQ Hosting using crypto currency
Installation
You can use either this command
[ -f "sixgpt.sh" ] && rm sixgpt.sh; curl -s -o sixgpt.sh https://raw.githubusercontent.com/zunxbt/sixgpt/main/sixgpt.sh && chmod +x sixgpt.sh && ./sixgpt.sh
Or this command to run this script
[ -f "sixgpt.sh" ] && rm sixgpt.sh; wget -q https://raw.githubusercontent.com/zunxbt/sixgpt/main/sixgpt.sh && chmod +x sixgpt.sh && ./sixgpt.sh
Imp Note
During the execution of the script, you will be prompted to enter the network name like this Enter Vana Network (satori or moksha)

If you requested the faucet for the Moksha network, type moksha
If you requested the faucet for the Satori network, type satori
Miner Status
Use this command
sudo docker logs ollama -f -n 50
If you get output like this, it is working fine
image
