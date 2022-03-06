# Site under construction
More on the way!

# About Higgsino Collectible Clips (NFT's)
A video/article consists of many individual clips. These clips will be available to collect as an NFT.

Supply of 100 per clip. 5% on re-sale.

[Browse NFTs here.](https://opensea.io/assets/higgsino)

Why should you buy Higgsino Collectible Clips? If you want to support the cause. The aim for is to contunie the project without sponsors or ads. Making "Collectible Clips" as NFT's further motivates to create even better animations.


# Available NFTS

{% for nft in site.nfts %}
  <h2><a href="{{ nft.sale_link }} ">{{ nft.number }} {{ nft.category }} {{ nft.name }} </a></h2>
  <p>{{ nft.description }}</p>
  <a href="{{ nft.sale_link }} "><img src="assets/img/{{ nft.file_name }}" alt="{{ nft.name }}"></a>
{% endfor %}
