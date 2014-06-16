chnroutes
=========

scripts help chinese netizen, who uses vpn to combat censorship, by modifying the route table so as routing only the censored ip to the vpn


autoproxy-gfwlist 维护被墙网站的列表；chnroutes 维护国内网站的路由表。前者有 PAC 文件，可以和代理配合，然而，逐个记录被墙的网站，总有漏网之鱼，而那些收到干扰或者直连很慢的网站也不能上榜。相比之下 chnroutes 就好一些，问题是它为 VPN 设计，只提供路由表，于是我修改了程序，生成 PAC。
