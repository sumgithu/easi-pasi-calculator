# EASI・PASI Calculator

皮膚科診療用のEASI（Eczema Area and Severity Index）・PASI（Psoriasis Area and Severity Index）計算サイトです。

## 仕様

- EASI / PASIをタブで切替
- EASIは8歳未満・8歳以上で部位係数を自動変更
- EASIは1.5、2.5の半点に対応（0.5は不可）
- PASIは0～4の整数評価
- 結果コピー、リセット機能
- スマートフォン対応
- 外部API・データベースなし。入力値はブラウザ内のみで計算

## EASI

各部位：頭頸部、上肢、体幹、下肢

4徴候：紅斑、浮腫／丘疹、掻破痕、苔癬化

各部位：`（4徴候の合計）× 面積スコア × 部位係数`

8歳以上：0.1 / 0.2 / 0.3 / 0.4

8歳未満：0.2 / 0.2 / 0.3 / 0.3

最大値72。

## PASI

4部位：頭頸部、上肢、体幹、下肢

3徴候：紅斑、肥厚／浸潤、鱗屑

各部位：`（3徴候の合計）× 面積スコア × 部位係数`

係数：0.1 / 0.2 / 0.3 / 0.4

最大値72。

## GitHub Pages

Repositoryのルートに `index.html`、`style.css`、`script.js`、`README.md` を置き、Settings → Pages → Deploy from a branch → `main` / `/ (root)` で公開できます。

## 参考文献

- Hanifin JM, Thurston M, Omoto M, Cherill R, Tofte SJ, Graeber M. The eczema area and severity index (EASI): assessment of reliability in atopic dermatitis. Exp Dermatol. 2001;10(1):11-18.
- HOME Initiative. EASI user guidance.
- Thomas KS, et al. The Eczema Area and Severity Index—A Practical Guide.
- Fredriksson T, Pettersson U. Severe psoriasis—oral therapy with a new retinoid. Dermatologica. 1978;157(4):238-244. doi:10.1159/000250839.
- DermNet NZ. Psoriasis Area and Severity Index (PASI).

## 注意

本サイトはEASI・PASIの計算補助ツールです。最終的な評価は診察時の臨床所見に基づいてください。評価者間差が生じる可能性があります。患者氏名・患者ID等の個人情報は入力しないでください。
