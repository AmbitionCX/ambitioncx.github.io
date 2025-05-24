---
title: "On the Latency Performance in Private Blockchain Networks"
collection: publications
category: manuscripts
permalink: /publication/2022-04-IoTJ-Latency
# excerpt: ''
date: 2022-04-07
venue: 'IEEE Internet of Things Journal'
link: 'https://ieeexplore.ieee.org/abstract/document/9751067'
paperurl: 'http://chenxuan.space/files/2022-04-IoTJ-Latency.pdf'
# slidesurl: ''
citation: '<strong>X. Chen</strong>, K. Nguyen and H. Sekiya, "On the Latency Performance in Private Blockchain Networks," in IEEE Internet of Things Journal, vol. 9, no. 19, pp. 19246-19259, 1 Oct.1, 2022.'
share: false
---

Blockchain technologies have been emerging with the potential to disrupt many fields (e.g., cryptocurrencies replacing the traditional ones, enabling trustworthy voting, etc.). The Internet of Things (IoT) has been predictably strengthened when integrating to the private blockchain, such as Ethereum. In an IoT deployment with private Ethereum, a thorough understanding of the latency is a critical issue that has not been adequately understood in the literature. Motivated by that, this work aims to comprehend the latency performance in the IoT Ethereum with two popular consensus algorithms: Proof of Work (PoW) and Proof of Authority (PoA). Initially, we clarify different latency segments from transaction submission to execution, namely, the
transaction lifecycle in a private blockchain. We then consider the three related latency metrics: 1. transaction-oriented latency; 2. mining time; and 3. block-oriented latency in the PoW case. With PoA, the mining time’s consideration is omitted since the mining process is not necessary. After that, we construct a realistic private Ethereum IoT network (i.e., using a laptop and seven Raspberry Pi 3b+ nodes) and a large-scale emulated one with 30 nodes. We write and deploy a smart contract to read and write data to the blockchain and measure the latencies in various scenarios. The measurement results reveal the values of transaction-oriented and block-oriented latency with PoW and PoA in both the actual and emulated networks. Moreover, we
derive the expected value for the PoW’s mining time by fitting the probabilities to an exponential curve.