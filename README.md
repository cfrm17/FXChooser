# FX Chooser

A FX choice option is an option that gives the holder the right of choosing to enter one and only one of the two underlying securities: a cross-currency swap or a cross-currency forward contract. Let us call the option an FX choice option. 

Let t ¸ 0 be a generic valuation time point and T > 0 be the maturity of the FX choice option. Let C, U and S be a base currency, a quote currency and exchange rate, respectively, where S is expressed in the American convention, i.e., S is the number of the base currency C per unit of the quote currency U. Let BC be the bond price process of a pre-determined fixed coupon bond with unit face value in the C-currency. 

To elaborate, the following parameters are given at time-0: the bond term, the bond effective date is time T, the coupon rate RC and the day-count-basis (DCB). Similarly, we define BU as the bond price process of a pre-determined fixed coupon bond with unit face value in the U-currency. Further, let NU be the principal amount in the U-currency and ˆ S be a fixed exchange rate. Both are given at time-0.

Now let us elaborate the two underlying securities. To enter the cross-currency forward contract, it means that the option holder will long NU units of the U-currency and short ˆ S*NU units of C-currency at time of T. In this case, the payoff in the C-currency can be given by

 N_u x (S(T) - S)

where S(T) is the spot exchange rate at the time T. To enter the cross-currency swap, it means that the option holder, at the time of T, will long the bond BU(T) with face value of NU and short the bond BC(T) with face value of NC(T) which is determined at the time of T.

Since the option holder will never exercise to enter neither of the two contract if it gives a negative payoff at the time of T, therefore, from the two sub-payoffs, we finally can define the option payoff in the C-currency at the maturity of T.

It is clear that the uncertainty of the option matured payoff is contributed by three random variables: the C-currency bond price BC(T), the U-currency bond price BU(T) and the cross-currency exchange rate S(T).

Let dfC be the discounting function in the C-currency world. Then, in the C-currency risk neutral world, the time-t value of the option, denoted by Vt, can be expressed

Hence, the key is to calculate the expectation of the matured payoff of (5). Let us elaborate in the following. For simplicity of notation, we use BC, BU and S instead of BC(T), BU(T) and S(T), respectively, and we set the valuation time at t = 0. 

Now let us introduce some assumptions. Let ¯BU(¢) be the forward price process of the bond BU and ¯BC(¢) be the forward price process of the bond BC. Both forward bond prices are matured at time of T such that ¯BU(T) = BU(T) and ¯BC(T) = BC(T).

Reference:

https://finpricing.com/product.html
