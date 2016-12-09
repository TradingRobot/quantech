# Quantech : a high-performance trading software
# ![image](tutorial/image/startup_screen.png)

# Introduction


# Main features

* programming in c++ integrated with intel TBB, berkeleyDB & QT
* base on CTP Api
* multiple account


# Installation


## Windows
clone/copy to your pc and install vc_redist.x86 which in the folder you cloned/copied


## Linux
to be done


## macOS
to be done


# Usage

double click the Quantech.exe to start the program


# Turorial
i'm sure you can learn this staff within 10 min

## Overview
when you start the program (i must confess the demo picture is suck)
![image](tutorial/image/main_screen.png)

press the account button, 
![image](tutorial/image/account.png)

## Detail
in the market data table, you can subscribe/unsubcribe the instrument you interest in (you must login first, or you
 will get nothing to subcribe), and the strategy only deal with the instrument you subcribed,
right click the instrument you subscribed to take an action, multiple selection is supported.
![image](tutorial/image/market_table.png)

in the position table, you take action such like close, close all, lock, overweight etc. attension: the action in position table
all make with market price type, so, if you use simulation account logined, your order will be rejected by the exchange, simulation
account can only use limit price type and GFD time in force. just right click to see what happen, multiple selection is supported.
![image](tutorial/image/position_table.png)

the most important table you should pay attention to is order table, it record what you have done and what the exchange
reply to your order, when something unexpected happen, you can cancel or cancel all your order, multiple selection is supported.
![image](tutorial/image/order_table.png)

there has a pretty and fancy dialog named input order dialog, it is compact and has full functionality about how you
can make your order
![image](tutorial/image/new_order.png)

## Special introduction

###what is order type and how to choose appropriate order type?
![image](tutorial/image/order_type.png)

###what is time in force and how to choose appropriate time in force?
![image](tutorial/image/time_in_force.png)


# Contact
trading_robot at outlook dot com

# License

Apache License 2.0 [license](license.txt)