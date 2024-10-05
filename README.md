# ChronicleProtocol-Sample
Chronicle Protocol調査用のリポジトリ

## クローン方法

```bash
git clone --recursive https://github.com/mashharuki/ChronicleProtocol-Sample.git
```

## ChronicleProtocolとは

Chronicle Protocolは、2017年以降、MakerDAOとそのエコシステムのために100億ドル以上の資産を独自に保護してきた革新的なオラクルソリューションです。Chronicle Protocolは、Ethereum上で最初のオラクルを発明するなど、常に革新を続けており、オラクルネットワークの概念を再定義しています。ブロックチェーンに依存しないこのプロトコルは、オンチェーンでのデータ転送における現行の制約を克服し、真にスケーラブルでコスト効率が高く、分散化された検証可能なオラクルを開発することで、データの透明性とアクセスのあり方を大きく変えています。

### コスト効率
他のオラクルは、検証者の数と署名の数が一対一の関係になる楕円曲線デジタル署名アルゴリズム（ECDSA）に依存していますが、ScribeはSchnorr署名暗号の革新的な応用を利用しています。これにより、スケーラブルな検証者の署名を1つの「スーパー署名」に統合し、それをECDSAで検証することができます。その結果、どれだけの検証者が関与しても、オラクルの更新にかかるガスコストはほぼ一定に保たれます。

### スケーラビリティ

Schnorr署名暗号の巧妙な応用により、Chronicleオラクルは、検証者の数とガスコストを切り離すことでスケーラビリティを実現しています。

### 検証可能なデータ

ダッシュボードでは、あらゆるレベルでデータの検証が可能です。ユーザーはブラウザで任意の検証者の署名を暗号的に検証できるだけでなく、対応するオラクルにオンチェーンで価格を反映させるために使用されたSchnorr署名も検証できます。

### 簡単導入

このプロトコルの設計は、アクセスのしやすさを重視しています。Chronicleはブロックチェーンに依存しないプロトコルで、ほぼすべてのチェーンに簡単に展開できます。Chronicleオラクルはシームレスな統合機能を提供しており、サポートされているチェーンの既存プロトコルに数分で組み込むことが可能です。

### 分散化

Chronicleの検証者はコミュニティによって運営されています。検証者の数とガスコストが切り離されているため、Chronicleはより高度な分散化を実現し、より高いセキュリティと回復力を、ほぼ一定のコストで提供します。

### 信頼性と安全性

Chronicleの検証者は、MakerDAO、Infura、Gitcoin、Etherscan、Gnosis、DeFi Saverなど、ブロックチェーンの主要プロトコルのコミュニティによって構成されています。このアプローチはChronicle独自のもので、オラクルデータが最も信頼性の高いプロジェクトによって署名されていることを保証し、プロトコルへの信頼をさらに強化しています。

Chronicleは、総資産担保額（TVS）で2番目に大きいオラクルプロバイダーであり、現在、MakerDAOなどの信頼性の高いプロトコルに対して約60億ドルを保護しています。

### 参考文献
1. [ダッシュボード](https://chroniclelabs.org/dashboard)
2. [ドキュメント](https://docs.chroniclelabs.org)
3. [whitelistAddress](https://docs.chroniclelabs.org/Developers/Guides/whitelistAddress)
4. [Testnet Contract addresses](https://docs.chroniclelabs.org/Developers/testnet)
5. [eth-global-sf-hackathon resources](https://docs.chroniclelabs.org/hackathons/eth-global-sf-hackathon)
6. [GitHub - scaffold-oracle-reader](https://github.com/chronicleprotocol/scaffold-oracle-reader)
7. [GitHub - chronicleprotocol](https://github.com/chronicleprotocol)