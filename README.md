# ExJpeg

#### Exploring JPEGs

## Problem
The current NFT/JPEG exploration ecosystem is based on a set of pre-defined filters (e.g. Hat/Skin/Body/... type), which works fine in most cases.

But what if you'd like to filter and identify JPEGs based on a more visual trait? For example, [hashmasks with a clown mask](https://clownbanks.com/)? Not possible with the current tooling ecosystem (let me know if you find one tho).

## Solution(?)
As I couldn't really find a curation tool that I was satisfied with, I built one -- ExJpeg. It uses proven machine learning techniques to project the images (high dimensional data) onto a 2 dimensional manifold. In theory, images with similar visual properties should cluster together. This allows for easier curation / exploration 

The model used in the project will be open sourced in due time.

# Run locally

```
git clone https://github.com/libevm/exjpeg.git
cd exjpeg

python3 -m http.server
```