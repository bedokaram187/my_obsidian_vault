---
{"dg-publish":true,"permalink":"/information-theory/channel-capacity/"}
---


>maximum rate at which reliable transmission of information over the channel is possible

>the maximum of mutual information $I(X;Y)$ measured in bit/symbol

## Shannon capacity (transmission over noisy channel) 
$$C = Blog_2(1+ \frac{S}{N})$$

$$I(X;Y) = H(Y) - H(Y/X)$$
$$ = H(Y) - \sum p(x)H(Y/X=x)$$ $$ = H(Y) - \sum p(x) H(p)$$
$$ = H(Y) - H(p)$$
$$ \le 1 - H(p)$$ 
