[![DOI](https://sandbox.zenodo.org/badge/496327256.svg)](https://sandbox.zenodo.org/badge/latestdoi/496327256)


# DATASET: RePEc inequality narratives on Twitter

This repostiory contains the list of Tweet IDs of the Tweets about inequality published by economists in the RePEc list. 
This dataset has been collected for the [MUHAI project](https://muhai.univiu.org/), in relation to the creation of a  social inequality observatory. 
This dataset is used in the working paper titled "How RePEc economists conceptualise and discuss inequalities on Twitter", by Carlo R. M. A. Santagiustina. <br><br>
Tweets in this dataset can be freely retrieved, with their IDs, using the GET /2/tweets/:id API endpoint (more info at this link: https://developer.twitter.com/en/docs/twitter-api/tweets/lookup/api-reference/get-tweets-id).<br><br>
These Twitter posts were published from the beginning of January 2010 to the end of July 2021, and were collected with R using the [Twitter FullArchive API endpoint V2](https://developer.twitter.com/en/docs/twitter-api/tweets/search/quick-start/full-archive-search). <br><br>
Our Twitter query was based on the [RePEc economists](https://twitter.com/i/lists/1087053821786947584/members) Twitter list of profiles and the following keyword filtering conditions: (unequal OR inequal OR inequalities OR inequality OR iniquity OR iniquities OR iniquitous OR disparity) lang:en -is:retweet from: [iterate on users in the RePEc economists list]<br><br>


For additional information please contact: [Carlo R. M. A. Santagiustina - carlo.santagiustina@univiu.org](mailto:carlo.santagiustina@univiu.org)
