# AnimatorRotarySwitch
**これは暫定版です。動作の保証はできません。**

## これはなに？
VRChatのアバターに仕込むことでs、ハンドサインなどを使って複数のオブジェクトの中から一つをONにしたりするシステムです。
ハンドサインを出している間はオブジェクトを順番に切り替え、やめた瞬間のオブジェクトが表示されます。
EmoteSwitch の原理を応用しています。（See Also: https://note.com/gend/n/nabcad7279bc2）

## せってい
1. プロジェクトに [`AnimatorRotarySwitch.unitypackage`](https://github.com/esnya/vrc-animator-rotary-switch/raw/master/AnimatorRotarySwitch.unitypackage) を追加
2. `AnimatorRotarySwitch/RotarySwitch.prefab` をアバターの直下に配置
3. 各Slot（Slot1～SlotN）に出し入れしたいオブジェクトを配置
4. `AnimatorRotarySwitch/Rotate.anim` のアニメーションをコピーして、任意のハンドサインのアニメーションに貼り付け。

## ついかいかた
きっとわかる

## ちゅうい
* 時々同期ズレあります。
* Slotの増減をしたら `AnimatorRotarySwitch/RotarySwitch.anim` を編集
* ↑をもっと早くする事もできるけれど、早すぎると同期ずれしやすい。ON→OFF0.5秒が限界かもしれない。

## らいせんす
MITライセンスです。ざっくり言えば、自己責任で自由に使ってくださいというやつです。
