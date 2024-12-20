﻿# LookAtRig

#### **Namespace**: Unity.TinyCharacterController.Ik
---

## 概要:
`LookAtRig` は、キャラクターが特定のターゲットを視線で追跡するためのコンポーネントです。逆運動学(IK)を使用して、キャラクターの頭部や目がターゲットの方向を向くようにします。視線の追跡は、自然なキャラクターの振る舞いを作り出すためにしばしば使用されます。

## 機能と操作:
- **視線追跡**: ターゲットを視線で追跡し、キャラクターが自然にターゲットを見るようにします。
- **重みと範囲の調整**: 視線の重みとクランプ角度を調整し、視線の動きを制御します。

## プロパティ
| 名前 | 説明 |
|------|-------------|
| `IsWork` | 視線をターゲットに向けるかどうかのフラグ。 |
| `Target` | 視線を向ける対象の `Transform`。 |
| `TransitionTime` | 視線のON/OFFを切り替える時間。 |
| `bodyWeight` | 身体の重み。視線の追跡に身体がどの程度影響するか。 |
| `headWeight` | 頭部の重み。視線の追跡に頭部がどの程度影響するか。 |
| `eyeWeight` | 目の重み。視線の追跡に目がどの程度影響するか。 |
| `clampAngle` | 視線のクランプ角度。視線の動きを制限する角度。 |

## メソッド
- 公開されているメソッドはありません。

---
## その他の注意事項
- `LookAtRig` は `IIkRig` インターフェイスを実装しており、IK処理の基本的なフレームワークを提供します。
- 視線の追跡は、キャラクターの挙動にリアリズムと没入感を加えるために重要です。適切な重みとクランプ角度の設定により、自然な視線の動きを実現できます。
