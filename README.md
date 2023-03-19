# Identification of the Breach of Short-Term Rental Regulations in Irish Rent Pressure Zones

## Abstract

The housing crisis in Ireland has rapidly grown in recent years. To make a more significant profit, many landlords are no longer renting out their houses under long-term tenancies but under short-term tenancies. The shift from long-term to short-term rentals has harmed the supply of private housing rentals. Regulating rentals in Rent Pressure Zones with the highest and rising rents is becoming a tricky issue.

In this paper, we develop a breach identifier to check short-term rentals located in Rent Pressure Zones with potential breaches only using publicly available data from *Airbnb* (an online marketplace focused on short-term home-stays) and Irish government websites. First, we use a Residual Neural Network to filter out outdoor landscape photos that negatively impact identifying whether an owner has multiple rentals in a Rent Pressure Zone. Second, a Siamese Neural Network is used to compare the similarity of indoor photos to determine if multiple rental posts correspond to the same residence. Next, we use the Haversine algorithm to locate short-term rentals within a circle centered on the coordinate of a permit. Short-term rentals with a permit will not be restricted. Finally, we improve the occupancy estimation model combined with sentiment analysis, which may provide higher accuracy.

## Citing

- [*arXiv*](https://arxiv.org/abs/2211.16617)

  ```tex
  @misc{liu-2022:irish-rent-breach,
      title     = {Identification of the Breach of Short-term Rental Regulations in Irish Rent Pressure Zones},
      author    = {Liu, Guowen and Arnedillo-Sanchez, Inmaculada and Chen, Zhenshuo},
      year      = 2022,
      publisher = {arXiv},
      doi       = {10.48550/ARXIV.2211.16617},
      url       = {https://arxiv.org/abs/2211.16617},
      copyright = {arXiv.org perpetual, non-exclusive license}
  }
  ```

- [*Journal of Computer and Communications*](https://doi.org/10.4236/jcc.2023.112002)

  ```tex
  @article{liu-2023:irish-rent-breach,
      title     = {Identification of the Breach of Short-Term Rental Regulations in Irish Rent Pressure Zones},
      author    = {Liu, Guowen and Arnedillo-S{\'a}nchez, Inmaculada and Chen, Zhenshuo},
      year      = 2023,
      journal   = {Journal of Computer and Communications},
      publisher = {Scientific Research Publishing, Inc.},
      volume    = 11,
      number    = 02,
      pages     = {8--19}
  }
  ```