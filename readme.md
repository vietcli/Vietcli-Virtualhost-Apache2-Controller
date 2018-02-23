# Vietcli
[![N|Solid](http://www.vietcli.com/wp-content/uploads/2018/02/vietcli-logo1.png)](http://www.vietcli.com)

This is a script to create and delete apache virtualhost more quickly (tested on Ubuntu 14.04).

## Getting Started

This script is used when your system have already had Apache on Ubuntu. And you have root permission as well. You can create and delete virtualhost with single command by using this script.

### Prerequisites

What things you need to install and how to install.

***Apache2**
***Openssl**

### Installing

Using WGET

```
$ sudo bash -c "wget -O /usr/local/sbin/vietcli https://raw.githubusercontent.com/vietcli/Vietcli-Virtualhost-Apache2-Controller/master/vietcli.sh && chmod +x /usr/local/sbin/vietcli"
```
OR
```
$ wget -q --no-check-certificate https://raw.githubusercontent.com/vietcli/Vietcli-Virtualhost-Apache2-Controller/master/vietcli.sh
$ chmod +x vietcli.sh
$ sudo mv vietcli.sh /usr/local/sbin/vietcli-d
```
Using CURL

```
$ sudo bash -c "curl -L https://raw.githubusercontent.com/vietcli/Vietcli-Virtualhost-Apache2-Controller/master/vietcli.sh -o /usr/local/sbin/vietcli && chmod +x /usr/local/sbin/vietcli"
```
OR
```
$ curl -L https://raw.githubusercontent.com/vietcli/Vietcli-Virtualhost-Apache2-Controller/master/vietcli.sh
$ chmod +x vietcli.sh
$ sudo mv vietcli.sh /usr/local/sbin/vietcli
```

## Running the tests

```
$ sudo vietcli create www.my-domain.com
```
OR
```
$ sudo vietcli delete www.my-domain.com
```

## Authors

*   **Viet Duong** - *Initial work* - Visit [Viet Duong][1] site.

## License

This project is licensed under the MIT License - see the <LICENSE.md> file for details

 [1]: http://www.vietduong.net/
