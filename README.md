Description
===========

Cloudflare app to include [instant.page](https://instant.page) library - [click here to install](https://www.cloudflare.com/apps/instant-page-app) on your website.

[instant.page](https://instant.page) is a free and open source library that uses just-in-time preloading, meaning it preloads a page right before a user clicks on it. Pages are preloaded only when there's a good chance that a user will visit them, and only the HTML is preloaded, being respectful of your users' and servers' bandwidth and CPU. It uses passive event listeners so that your pages stay smooth and doesn't preload when the user has data saver enabled.

Status
======

[![Version](https://img.shields.io/badge/version-1.2.2-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAAGXcA1uAAAACXBIWXMAABYlAAAWJQFJUiTwAAAFiElEQVR42n1VW0xUVxTdM8NDCihGg6AtyEt8oIKIpQIp4oviawQbsCgGVGisH/pj0tpiavzSpk2TtknVtKYf1cZ+tNImpSYmaovIM37YoiEqtinFe+4dZqCE1sLu2ufemcE29iZn7j1n9l57n33W2oe6fExqWgOpGC+REX+ATNrMFhUyWbQBk0JMMph+ZCbTU8OdY0z4p5rlsWipmJXx+PlWNimZ6bqYUQOLhUElWCxjFVnCNJiwD39s4eDjm7/OBu4cYXoU9SJb7jy9IDCXPv2eqdsE1LQ6UrF7kVcN/XShnSRZGqYqBN0F60oeO/E53sXcd+oihRePn2dFy/Cdz8qTIylWspVaEwpu0SKM5yTVcnyU8Pi5FgTOwncKD85cwPSg8ji8VgAmRS+OkIu7kSl1IaubfzL5yUsqYj/bMat1XJM24r2BVUw5P/QepQ6plTHjNVKRjU8YKhg97r3HpmutDm/pKq8AAOppxDdS0NCirewvPqyT/vvBII8eeo/H3vjQyXUh3qjgo5idcJBDK8dCMdBzMPK108ieN7G2SFdW9qFoLlPPjfuk3GWh0IoyeSIwive8kKEcQ4Dc/M1XN1mXXTZzt/kM9rKcVURO2NCVzEPxqfzthWvcHZikTkuqBAdhyu0vbpHlqsWe9oM9taxia9mIrSIzeqNmlJyxPlNBf+j9iEx3A/ayB8g7MXZgbMN4CRwq52FaqksvR0B9J6+QEXMAxnUweMUx9rK/5Aj2sRrfpdjDavZTqiYlON70H2MFdk6O/4V3MebiVIC9FfCjpDVw8DQ4xi/rNAxaZZd0+1uYF2lji3IxFsNpiZBpqvELPOmwbfTgKf7j0LvsX12PlJbg/yw24nLEwTZWtJYnrBGe+kz4As55LMCYD1aCGsq1HZMKm2S0HFHSecL0aweDZoeMTTgqd7IIy4uF9boakrOBk5ZH4XSDxhaMfTSdv/u4BQ7xXqS1JrTBQPlBtmbJRrMx0rSxRYn8c3Eltw2NE7WjtsOUBadVCJvLvnlleAeNn8WYzf35G7i17R51DQs1wI/2CexlxkoyosF5VzgN0zWHe2oP89W2u9Tld6ghP+IkFLkJx/5jLaRmgk9R9aSi9hWZHpTVtZvt8lfrwzVFjS4vm56tUCOOI24rfDZRf/NnGkOwBNPmHnQt2xioOm3LOrLJ6WF1jmrDwLbMhTnrsFX8767AXFrZGgQsZTVtPSiXCaxmjdkRQIDeG7+QMR1tIBrA7r1PBbYpieLPqoQex1D8o5gXOKdX4lD0eda1Rrs0Youo59YAAbQeYngVWT8d2BQVAWD8/FVNgfFzraBDLtaDwIUOpfM1raUXqag8UCMVTSymkUxXnSPLaofmlZq90tUNOI7seSfMXkvYW4j1NLyzMDIc6q/Ql4alv7NZubLZeAbMNiN2IfsngaX5iTJ982shhyfl8e9HAlqppU6ghQ65M2w1eNLl/qlHgCoHeAuM5OBKIcpD6KhnIdAP0F3fh1hPotP+FgIWEfuLd2Mnc5xrIwwsV4hIbTBhMdp21A4yIrbrbmXpa0VkVzbl8IqQXTbax5EQ+Njx01q3tmCmAqfYeqAklCiJf52bC2kmVJOicjI8FZpuU4HtLp4HCubrhva49w7m6RhpjnQzHEUGgZO1MgMUwR1Nx/jL7iGiH8DXvlNfQ85L0DjW6fYZZIUpVymax9iJM2ixdcg68X+AE3mUiO8WbuZL5y7zte6H1Dvh3J2ivHY08YFtryNQKlraStzRBQ4rFgMgfUopwsAWSuGjBFzEbr5TuIlbPmnly1duUxeuHGkVoWtHDwTqHGW9o1stHaTiluIaysRNuYyH4pbz7zNy2YjKxEjH90IIKQV3WBpfffs0X2wboOv3R6hnkkPAQdx/ADtoOjMqs7MCAAAAAElFTkSuQmCC)](https://instant.page) [![Up votes](https://img.shields.io/badge/up%20votes-7-green.svg?logo=cloudflare)](https://www.cloudflare.com/apps/instant-page-app) [![Down votes](https://img.shields.io/badge/down%20votes-0-red.svg?logo=cloudflare)](https://www.cloudflare.com/apps/instant-page-app)

Requirements
============

* [Cloudflare](https://www.cloudflare.com)


Treat me to a beer!
===================

[![PayPal](https://img.shields.io/badge/PayPal-Donate-blue.svg?logo=paypal)](https://www.paypal.me/riklewis)
