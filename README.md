

### Güncelleme
```
cd
sudo systemctl stop viper.service
```
```
rm -rf /usr/local/bin/viper
wget -O /usr/local/bin/viper https://nodesrun.com/viper
chmod +x /usr/local/bin/viper
```
```
viper network version
```

PT- 0.1.3



```
sudo systemctl daemon-reload
sudo systemctl restart viper.service
journalctl -u viper -f
```
