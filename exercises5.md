## Exercises for session 5

1. Only using `scipy.special.yn`, plot the zeroth-order Bessel
   function of the second kind, and use fsolve to find the value of
   the third root, i.e. the third lowest value of $x$ where $Y_0(x) =
   0$.
2. Use `scipy.interpolate.quad` to find the integral of $Y_0(x)$
   between $x=0$ and the third root.
3. Use `scipy.stats.norm.rvs` to create 100 samples from a Normal
   distribution for some mean and sigma. Then use `plt.hist` to create
   a 10-bin histogram of the samples (see the return
   values). Determine the centre of each bin.
4. Create a function `f((m, s), a, x, y)` which returns the sum of the
   squared residuals between the values in `y` and a Gaussian with
   mean `m`, sigma `s` and amplitude `a`, evaluated at `x`.
5. Use the function you created in (5) with `scipy.optimize.minimize`
   to fit a Gaussian to the histogram created in (4).  Plot and
   compare with the result of using `scipy.stats.norm.fit`.
