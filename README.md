Market Quotes
Setting the stage
For illustration purposes, I’ll create a bond curve using the same data and algorithm shown in one of the QuantLib C++ examples; namely, I’ll give to the curve the functional form defined by the Nelson-Siegel model and I’ll fit it to a number of bond. Here are the maturities in years and the coupons of the bonds I’ll use:
For simplicity, I’ll use the same start date, frequency and conventions for all the bonds; this doesn’t

affect the point I’m going to make in the rest of the notebook. I’ll also assume that all bonds currently

price at 100. I’ll skip over the details of building the curve now; the one thing you’ll need to remember is that it depends on the quotes modeling the bond prices.
