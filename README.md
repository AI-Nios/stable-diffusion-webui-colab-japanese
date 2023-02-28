# stable-diffusion-webui-colab-japan

### colabでstable-diffusion-webuiと公開されている様々な学習済みcheckpointファイルを簡単に導入でき、日本人向けに使いやすくしたものです。
 Twitter→ https://twitter.com/ai_nios/status/1617901380370587654 <br>
 note→　https://note.com/ai_nios/n/n0826a33edc8a
## 🦒 Colab
| Colab Page 
| --- 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_Model_Card_Selection.ipynb) Nios_Model_Card_Selection.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_v2_update.ipynb) Nios_v2_update.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_v3.ipynb) Nios_v3.ipynb

## 各種説明
### Nios_Model_Card_Selection.ipynbの使い方
使用方法:noteに記載 URL → https://note.com/ai_nios/n/n0826a33edc8a 
### Nios_v2_update.ipynb
Nios_Model_Card_Selection.ipynbのプログラムに加え、公開されてる学習済みのLoRAやTextual InversionをColab上から選択してダウンロードできます。<br>
ControlNetも使用できます。
### Nios_v3.ipynb
https://github.com/camenduru/stable-diffusion-webui-colab/tree/v2.0 のColabのプログラムコードに基づき、Nios_v2_update.ipynbと同じ感覚で使用できるようにしたものになります。<br>

## 追加・変更のお知らせ
### 2023/02/05<br>
EasyNegative追加。ネガティブプロンプトにEasyNegativeといれることにより余計な否定プロンプトを書かなくてよくなりました。<br>
### 2023/02/10<br>
WebUI拡張機能 Aspect Ratio selectorの追加。画像のアスペクト比セレクター ボタンを追加しました。1:2,2:3,9:16など<br>
WebUI拡張機能 images-browserの追加。WebUI起動後から現在までに生成された画像を閲覧することができます。<br>
### 2023/02/18<br>
WebUI拡張機能 Push to 🤗 Hugging Faceの追加。WebUI上からモデルやVAE、LoRAを追加することができます。<br>

## 対応モデル名(Nios_v2_update.ipynb以降）<br>
"stable_diffusion_v1.5","stable_diffusion_v2.1","waifu_diffusion_v1.3","Openjourney","anything-v3.0","anything-v4.0","anything-v4.5","Counterfeit-V2.0","Counterfeit-V2.5","8528-diffusion","AbyssOrangeMix2","EerieOrangeMix2","trinart2_step115000","Eimis Anime Diffusion_1.0v","dreamlike-photoreal-2.0","Cyberpunk-Anime-Diffusion","Plat Diffusion v1.3.1","ACertainThing","pastel_mix","Basil_mix_fixed","Realistic Vision V1.3","SukiyakiMix-v1.0","7th_anime_v1.1", "7th_anime_v2_A", "7th_anime_v2_B", "7th_anime_v2_C", "7th_anime_v2_G", "7th_anime_v3_A", "7th_anime_v3_B", "7th_anime_v3_C","7th_anime_3.1_B","YuzuGinger_v4","YuzuLemonMilk_v1.5", "Defmix-v1.1","RDtMix","meadmix","Nabylon-v1.0","LonganMix","Corneo's 7th Heaven Mix", "Corneo's Shinra26 Mix","atwmix_test2","Graham_Special","ACertainModel","BalorV2featAbyssOrange2","Balor-V2.5featAOM3A3"
