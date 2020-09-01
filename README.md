# Clover_catalina
Clover Catalina config
config.plist 
GigaByte GA-170X-Gaming 5
Intel HD Graphics 530 1536 MB

Download astra 5.63

cesbo.com/download/astra/5.63/x86_64/astra

put in /usr/bin chmod 755

/etc/astra/license.txt

{"l":"aabbccede0a000b08569333774411edd","e":"fuck@astra-cesbo.com"}

/etc/hosts
127.0.0.1 ls1.cesbo.com
127.0.0.1 ls2.cesbo.com
127.0.0.1 ls3.cesbo.com

/etc/rc.local
/sbin/iptables -t nat -I OUTPUT --dest 104.131.182.84/28 -j DNAT --to-destination 127.0.0.1
/sbin/iptables -t nat -I OUTPUT --dest 78.128.94.139/28 -j DNAT --to-destination 127.0.0.1
/sbin/iptables -t nat -I OUTPUT --dest 104.248.91.131/28 -j DNAT --to-destination 127.0.0.1
