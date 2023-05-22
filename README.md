# hbm_analysis
Upload all algorithms concerned with Harmonic balance method

1. Fast-exact algorithm for HBM analysis for ODEs with polynomial nonlinearities
2. Simple HBM analysis for black-box ODEs (with Jacobian) based on quadarature

Fast exact algorithm
$$
\cos^{m-l}(x)\sin^l(x)=\Re\left[\frac{(-i)^l}{2^m}\sum_{p=0}^m\left[\sum_{q=0}^p(-1)^q\binom{m-l}{p-q}\binom{l}{q}\right](\cos((2p-m)x)+i\sin((2p-m)x))\right].
$$