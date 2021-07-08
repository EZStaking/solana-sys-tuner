# solana-sys-tuner

### This little tutorial assumes that your user is "sol". If not, change everywhere where "sol" is by the name of your user Solana.

# Clone this repository
`git clone https://github.com/EZStaking/solana-sys-tuner.git && cd solana-sys-tuner`

## Copy

`cp bin/sys-tuner.sh /home/sol/bin && chmod +x /home/sol/bin/sys-tuner.sh && sudo cp service/solana-sys-tuner.service /etc/systemd/system`


## Enable service 
`sudo systemctl enable solana-sys-tuner && sudo systemctl start solana-sys-tuner`

## Check that everything works
`sudo systemctl status solana-sys-tuner`

## Watch logs
`sudo tail -f /home/sol/sys-tuner.log`
