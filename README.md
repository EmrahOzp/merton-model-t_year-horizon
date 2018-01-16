# merton-model-t_year-horizon
calibrating multi period model to equity value and equity volatility

typically, the average maturity of a firm's debt is larger than 1 year. But, it is dubious to get better results from merton model if we allign the maturity inside the modelwith actual debt maturities. 

It is safe to ignore the interim payments over a horizon of one year, however for a horizon of several years interim payments should enter our valuation formula. 

the main set-up of the merton model in the sense that there is only one date at which liabilities are due. however, we take interim payments into account.

assumptions are:
-assume that the firm has issued only one coupon bond with maturity equal to the average maturity of liabilities.
-accrue interest and dividend paymens to the maturity assumed in step 1; i.e shift their payment dates into the future
-since accrued interest and dividend payments are assumed to be due at maturity , eventhough they are actually paid before , treat them as liabilities have higher priority than the principal of the bond
