
# catherinejorg.ch

Backup de la version sur Aladin.net

<http://catherinejorg.ch/>

<https://catherinejorg.github.io/siteweb-aladin/>



## Config DNS chez Infomaniak — version Aladin

dns1.alk02.com
dns2.alk02.com

---

; Domain: catherinejorg.ch
; Exported (y-m-d hh:mm:ss): 2017-02-09 10:58:43
; Actual version

$TTL 10800
@      IN SOA dns1.alk02.com. cat\.jorg.hotmail.com. (1425550174 10800 3600 604800 10800)
 3600 IN NS dns1.alk02.com.
 3600 IN NS dns2.alk02.com.

---

ping -c1 catherinejorg.ch
PING catherinejorg.ch (213.221.157.93): 56 data bytes

--- catherinejorg.ch ping statistics ---
1 packets transmitted, 0 packets received, 100.0% packet loss



## Config DNS chez Infomaniak — version GitHub

ns11.infomaniak.ch
ns12.infomaniak.ch

---

; Domain: catherinejorg.ch
; Exported (y-m-d hh:mm:ss): 2017-02-09 11:01:55
; Actual version

$TTL 3600
@    IN SOA  ns11.infomaniak.ch. hostmaster.infomaniak.ch. (2017020900 10800 3600 605800 3600)
     IN A    192.30.252.153
     IN A    192.30.252.154
     IN NS   ns11.infomaniak.ch.
     IN NS   ns12.infomaniak.ch.
www  IN A    93.88.246.161
www  IN AAAA 2001:1600:2:c::117
www  IN TXT  "1|catherinejorg.ch"


