# Text2Playlist: Generating Personalized Playlists from Text on Deezer

This repository will contain resources related to the paper: _"Text2Playlist: Generating Personalized Playlists from Text on Deezer"_ by Mathieu Delcluze, Antoine Khoury, Clémence Vast, Valerio Arnaudo, Léa Briand,  Walid Bendada, and Thomas Bouabça

This work has been accepted for presentation as an "Industry Talk" at the 47th European Conference on Information Retrieval  ([ECIR 2025](https://www.ecir2025.org/)) in Lucca.

<p align="center">
  <img height="150" src="figures/ecir.png">
</p>


## Summary 

The streaming service Deezer heavily relies on the search to help users navigate through its extensive music catalog. Nonetheless, it is primarily designed to find specific items and does not lead directly to a smooth listening experience. We present Text2Playlist, a stand-alone tool that addresses these limitations. Text2Playlist leverages generative AI, music information retrieval and recommendation systems to generate query-specific and personalized playlists, successfully deployed at scale.

In this paper, we present Text2Playlist, illustrated in the Figure below, a personalized playlist creation tool, explicitly dedicated for broad intent queries, distinct from the search feature. It takes advantage of the recent rise of Large-Language Models (LLMs) and gets inspiration from Retrieval-Augmentation Generation (RAG) framework. Text2Playlist has been deployed on Deezer mobile and web applications for a first test phase of 5\% of premium users since July 2024 and 20\% since October 2024. This paper is organized as follows. In Section 2, we further detail our motivations for such a system. In Section 3 we detail how we use together query extraction, various metadata sources, Deezer recommendation system and LLMs to build this solution. In Section 4, we explain how Text2Playlist is deployed on Deezer and present analysis based on the first data gathered. We conclude and discuss areas of improvement in Section 5.

<p align="center">
  <img height="250" src="figures/generativeaiproto.png">
</p>


## Paper

The paper is publicly available [on arXiv]().

## Slides

Slides from the oral presentation are publicly available [here](https://github.com/deezer/text2playlist-ecir2025/blob/main/slides/delcluze_ecir2025.pdf).


## Video

_Soon._

## Citation

_Soon._

