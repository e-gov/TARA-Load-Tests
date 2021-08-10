## [DEPRECATED] TARA Load tests

JMeter test kombineeritud_v5.jmx combines load testing authentication via ID-card, mobile-ID and banklinks. Following variables can be adjusted in the User Defined Variables:


| Variable | Default Value | Description  |
| ------------- |:-------------:| -----|
| client_id | openIdDemo | Vajalik autentimise parameeter TARA kliendi pöördumisel serveri poole |
| client_name | CasOAuthClient | Vajalik autentimise parameeter TARA kliendi pöördumisel serveri poole |
| principalCode	| 01234567890 | Isikukood millega Mobiil-ID autentimist läbi viiakse |
| mobileNumber | 555 | Mobiilinumber, millega mobiil-ID autentimist läbi viiakse. |
| nonce	| qrstuvwxyzabcdef | Parameeter, millega pöördub tara server tagasi kliendi poole |
| state	| abcdefghijklmnop |Parameeter, millega pöördub tara server tagasi kliendi poole |
| host | koogelmoogel.net |Kasutatav server |
| port | 443 | Kasutatav port |
| protocol | https | HTTP/HTTPS |
| response_code | 200/302 | Assertioni tarvilik parameeter |
| bankhost | localhost | Pangalingi server url |
| bankport | 8990 | Pangalingi serveri port |
| redirect_uri | https://tara-client.arendus.kit:8451/oauth/response | Assertioni tarvilik parameeter |
| client_basic_auth | Basic b3BlbklkRGVtbzpzZWNyZXQ= | Identsustõendi päringu salasõna |
| duration | 15 | Testi kestvus sekundites |
| num_threads | 1 | Ühe autentimismeetodi theadide arv |
