# Site under construction
More on the way!

# About Higgsino Collectible Clips (NFT's)
A video/article consists of many individual clips. These clips will be available to collect as an NFT. Kind of like a limited digital supply of trading cards.

Supply of 100 per clip. 5% on re-sale.

[Browse NFTs here.](https://opensea.io/assets/higgsino)

Why should you buy Higgsino Collectible Clips? If you want to support the channel or think the clips will increase in value. The aim for Higgsino is to find a revenue stream without having sponsors and ads. Collectible Clips further motivates to create even better animations.


# Available NFTS

{% for nft in site.nfts %}
  <h2><a href="{{ nft.sale_link }} ">{{ nft.number }} {{ nft.category }} {{ nft.name }} </a></h2>
  <p>{{ nft.description }}</p>
  <a href="{{ nft.sale_link }} "><img src="assets/img/{{ nft.file_name }}" alt="{{ nft.name }}"></a>
{% endfor %}
