## Getting npm to work on a proxy server: 

* For http:

	npm config set proxy http://proxy_host:port

* For https:

	npm config set https-proxy http://proxy.company.com:8080


* To remove npm proxies:
	
	npm config rm proxy
	npm config rm https-proxy