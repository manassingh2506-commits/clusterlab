# ClusterLab

An interactive playground for k-means clustering. Click to add points, choose 2, 3 or 4 groups, and press Cluster to watch the algorithm move its centres step by step until the groups settle.

## How it works
1. Place k centres (chosen with the k-means++ method so they start far apart).
2. Assign every point to its nearest centre.
3. Move each centre to the mean position of its points.
4. Repeat steps 2 and 3 until no point changes group.

## Run it
Open `index.html` in any browser. There is nothing to install.

## Built with
JavaScript, HTML Canvas

Author: Manas Singh (26BDS0112), VIT Vellore
