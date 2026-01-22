# Artifact for the paper "On the Effectiveness of Mempool-based Transaction Auditing"

This repository contains raw transaction data captured by a set of 16 nodes and stored in their respective **mempools** in **Bitcoin** and **Ethereum**. 

## Contents

The repository includes the following files:

- `bitcoin_recordings.csv`  
  Contains a list of Bitcoin transactions identified by their transaction hashes (`tx_hex`) along with timestamps from 16 nodes (cf. [Node List](#node-list)), indicating when each (unconfirmed) transaction was first received.


- `ethereum_recordings.csv`  
Contains a list of Ethereum transactions identified by their transaction hashes (`tx_hex`) along with timestamps from 16 nodes (cf. [Node List](#node-list)), indicating when each (unconfirmed) transaction was first received.


## Structure

Each CSV file is structured with the following columns:
- `tx_hex` - The transaction hash, uniquely identifying the transaction
- `xxx{1-4}` - A timestamp recorded by a node upon first receiving the transaction. `xxx` denotes the node's location (cf. [Node List](#node-list)) followed by a number to differentiate between multiple nodes hoested at the same location. 


## Node List


| Node Identifier | Location                | Network Zone |
| :-------------: | :---------------------: | :----------: |
| hel1            | Tuusula (FI) - Node 1   | eu-north     |
| hel2            | Tuusula (FI) - Node 2   | eu-north     |
| hel3            | Tuusula (FI) - Node 3   | eu-north     |
| hel4            | Tuusula (FI) - Node 4   | eu-north     |
| us1             | Ashburn (VA) - Node 1   | us-east      |
| us2             | Ashburn (VA) - Node 2   | us-east      |
| us3             | Hillsboro (OR) - Node 3 | us-west      |
| us4             | Hillsboro (OR) - Node 4 | us-west      |
| sin1            | Singapore (SG) - Node 1 | asia         |
| sin2            | Singapore (SG) - Node 2 | asia         |
| sin3            | Singapore (SG) - Node 3 | asia         |
| sin4            | Singapore (SG) - Node 4 | asia         |
| nbg1            | Nuremberg (DE) - Node 1 | eu-central   |
| nbg2            | Nuremberg (DE) - Node 2 | eu-central   |
| nbg3            | Nuremberg (DE) - Node 3 | eu-central   |
| nbg4            | Nuremberg (DE) - Node 4 | eu-central   |

---



## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg



## Citation
```
@misc{albrecht2026effectivenessmempoolbasedtransactionauditing,
      title={On the Effectiveness of Mempool-based Transaction Auditing}, 
      author={Jannik Albrecht and Ghassan Karame},
      year={2026},
      eprint={2601.14996},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2601.14996}, 
}
```



## Contact

Feel free to contact the first author via the e-mail provided on the publication if you have any questions.
