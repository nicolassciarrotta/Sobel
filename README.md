# Sobel
Sobel filter

This project is divided into three parts:

<a href ="/src/main/java/sobel/centralizado/">Centralized Sobel</a> is a program which apply a filter sobel on an image and cut the image in parts indicated by user.

<a href="/src/main/java/sobelBalanceado/">Balanced Sobel</a> is implemented on RMI. This project implements a class Balanceador.Java. It's smart because it creates servers that apply the filter based on the number of cuts the user indicate.

<a href="/src/main/java/sobelRMI/">Sobel on RMI</a> is a mix of centralized and balanced whit the difference that is applied in a single server.
