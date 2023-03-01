# Hedging-Iterative-Intergals
This code enhances the Wiener-Ito chaos decomposition for diffusion processes that have a linear growth drift and diffusion coefficient. By relaxing the orthogonality constraint in the chaos expansion, we demonstrate that it's possible to represent any p-integrable functional with p between 1 and 1 as a sum of iterated integrals of the underlying process.

We utilize a truncated sum of expansion-based neural networks for the integrands and feed the resulting parameters into a machine learning framework. This approach provides proof of concept that financial derivatives can be approximated to an arbitrary degree of accuracy in the Lp sense. Additionally, we can compute the hedging strategy for approximating financial derivatives in a closed-form analytical manner.

European Option with Brownian Motion (BM)

<img width="550" alt="image" src="https://user-images.githubusercontent.com/42521586/222040711-23b376d8-aff6-4695-b176-6760c4c7f118.png">

Asian Option in Local Volatility Model (CEV)

<img width="550" alt="image" src="https://user-images.githubusercontent.com/42521586/222040322-f3c0b265-20db-4fe1-8bc6-1b30ad417291.png">

Basket Option in Affine Model (AM)

<img width="550" alt="image" src="https://user-images.githubusercontent.com/42521586/222040398-09255286-9f80-4932-b11f-f37493940eda.png">
<img width="550" alt="image" src="https://user-images.githubusercontent.com/42521586/222040461-9e7fed05-b13f-4647-8491-d16015334f0d.png">



