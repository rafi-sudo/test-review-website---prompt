# test-review-website---prompt
yuk kita mulai review situs web dari sisi teknis server side, stack yang digunakan ,tanpa review layout
kita mulai situs https:{situs}
GET / HTTP/3

Host: www.radiodahliafm.com

User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:128.0) Gecko/20100101 Firefox/128.0

Accept: text/html,application/xhtml+xml,application/xml;q=0.9,/;q=0.8

Accept-Language: id,en-US;q=0.7,en;q=0.3

Accept-Encoding: gzip, deflate, br, zstd

Referer: https://www.google.com/

DNT: 1

Sec-GPC: 1

Connection: keep-alive

Cookie: XSRF-TOKEN=eyJpdiI6Iittd1drRU1qbHFrc2cwZG1SaUdzZlE9PSIsInZhbHVlIjoiUWJJalJubWZ5MjFZODB3eFROWE5cL000VmxoazFoTEJNT25ZY0JVXC84MGQ1MHpQNjduS2dTdXhyelwvRWlueHRSRCIsIm1hYyI6IjcwN2FiZGRiNzNmMjg5MjQ5MzBkZWQyYjJiMjI5ODVjYmQ0MmYzY2Y4MmJhMGFlODlhMzEwMGI5ZDQ0YTAyZDEifQ%3D%3D; laravel_session=eyJpdiI6InVrejNGYWRXNUIzRWp3eE5DNTNFYXc9PSIsInZhbHVlIjoiQThOSHVBK1J1YTNEeW9hOGJrU1BUSmJLb1hxVGZablJzTHNCS3ZNVG1URGJkQ2VMQTVueXhGMkkzWUFEdkZtUlRvVTlDVGdzRHFtQTNvZklrZlE1MWZGMkFhSVRGdEw5RndYcTJ2OFVkdkVyV1NROXFBZ2ZzcFM1UFh1SnVUZnYiLCJtYWMiOiI0YWVmZWIxNTlhMmFmMGI4OTMwMDY2MGRiYzg2MGY1NDlhZTU0YjM1N2Q0NTI3NDc5OTg0OTQ3YjQxOWI0ZjdiIn0%3D; _ga_CVVLNRET0P=GS2.1.s1761648982$o1$g0$t1761648982$j60$l0$h0; _ga=GA1.1.537514536.1761648982

Upgrade-Insecure-Requests: 1

Sec-Fetch-Dest: document

Sec-Fetch-Mode: navigate

Sec-Fetch-Site: cross-site

Sec-Fetch-User: ?1

Priority: u=0, i

TE: trailers
(hasil response headers get) 

----------------------------
HTTP/3 200

cache-control: no-cache, private

content-type: text/html; charset=UTF-8

set-cookie: XSRF-TOKEN=eyJpdiI6InhjdEtaRHV5YTdSOUxoQUpQdkpNMHc9PSIsInZhbHVlIjoiK3E4Wm9vK1k2TVBIUzNTOE9MWjFZQUo5YmJwR1lCVnNxSkhNRSs3aXYzMjJicjJoWmdLXC9JRWF1eDBodXlGRU8iLCJtYWMiOiJhNDBlNDY1MTNiZGFhNjNlZDJkMGZmZTBlYWI0ODMxODhhMjRlOGE3YjUyYWNhZWQ3OTNjNTE3NzVlYjQ5ZTA3In0%3D; expires=Tue, 28-Oct-2025 12:52:31 GMT; Max-Age=7200; path=/; secure
laravel_session=eyJpdiI6IjJibnc1czQ4WjlMcWJVcEFLc0xnVFE9PSIsInZhbHVlIjoiVWtyVjBUNVwvNURNS2poa210WVFOVjY5WFk3eXlIUmNyTW9sMUtqZTdqa0ZXS05qUkJySlVwcXQ3NkxcL0IxWHVXRlZkb0hsNXNBRGtrNXduTmUxaCtPdTNKUW95cjl5QXRkTW1ZYUpLdjFkT2E2NlVuOE1pa2hCbDg3Z3NkYkZvRCIsIm1hYyI6ImZlZDUyYjZmMzRkMGY3Yzc5ZTY0Y2ZjOWNkN2RjMmI3NDViOWQ5NGIyNTY4YTViMDUzMTRjNWFhODllNmZmNjcifQ%3D%3D; expires=Tue, 28-Oct-2025 12:52:31 GMT; Max-Age=7200; path=/; httponly; secure

content-encoding: br

vary: Accept-Encoding

date: Tue, 28 Oct 2025 10:52:31 GMT

server: LiteSpeed

(hasil response fetch http/3 200 OK) 
step by step:
1. masuk developer mode di browser
2. masuk tab network (kita tidak akan bahas layout, kerangka, kita bahas aset dan komponen backen yang dipakai)
3. pilih tab html, lantas copy aset (salin response get http, dan fetch http)4. copy juga asset lainnya, terutama js atau backend program languange nya kecuali yang di embed.
4. copy juga asset lainnya, terutama js atau backend program languange nya kecuali yang di embed.
5. Salin juga jenis fontnya
6. Salin juga asset media ( salah satu)
7. saat salin get dan fetch, pasti IP origin akan muncul, lalu kita tes IP di browser apakah ada kerentanan?
# Case :
