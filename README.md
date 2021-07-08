# solana-sys-tuner

## Copy

`cp bin/sys-tuner.sh /home/sol/bin && chmod +x /home/sol/bin/sys-tuner.sh && sudo cp service/solana-sys-tuner.service /etc/systemd/system`


## Enable service 
`sudo systemctl enable solana-sys-tuner && sudo systemctl start solana-sys-tuner`

## Ensure everything is fine
`sudo systemctl status solana-sys-tuner`

## Watch logs
`sudo tail -f /home/sol/sys-tuner.log`
