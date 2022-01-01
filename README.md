```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/cobaltdisco/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh
```


```
nano /etc/snell/snell-server.conf
systemctl restart snell
```


```
systemctl status snell
```

卸载方法：

```
wget --no-check-certificate -O uninstall-snell.sh https://raw.githubusercontent.com/cobaltdisco/snell.sh/master/uninstall-snell.sh
chmod +x uninstall-snell.sh
./uninstall-snell.sh
```
