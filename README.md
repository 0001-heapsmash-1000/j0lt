# j0lt DNS amplification (DDoS) attack tool
 ------------------------------------------------------------
 > * the-scientist
 > * tofu@rootstorm.com
 ------------------------------------------------------------
 > Knowledge:
 > * https://datatracker.ietf.org/doc/html/rfc1700    (NUMBERS)
 > * https://datatracker.ietf.org/doc/html/rfc1035    (DNS)
 > * https://datatracker.ietf.org/doc/html/rfc1071    (CHECKSUM)
 > * https://www.rfc-editor.org/rfc/rfc768.html       (UDP)
 > * https://www.rfc-editor.org/rfc/rfc760            (IP)
 ------------------------------------------------------------
 > Usage: sudo ./j0lt <target> <port> <num-packets>
 > * (the-scientist㉿rs)-[~/0day]$ gcc j0lt.c -o j0lt
 > * (the-scientist㉿rs)-[~/0day]$ unshare -rn
 > * (the-scientist㉿rs)-[~/0day]# ./j0lt mod.gov.cn 80 1337
 ------------------------------------------------------------
 > What is DNS a amplification attack:
 > * A type of DDoS attack in which attackers use publicly
 > accessible open DNS servers to flood a target with DNS
 > response traffic. An attacker sends a DNS lookup request
 > to an open DNS server with the source address spoofed to
 > be the target’s address. When the DNS server sends the  
 > record response, it is sent to the target instead.
 ------------------------------------------------------------
 > Big hi to the only sane place left on the internet:
 * ## irc.efnet.org #c
