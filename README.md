# stable-diffusion-webui-colab-japanese

### Google ColaboratoryでStable Diffusion WebUIと様々な学習済みcheckpoint（safetensors）ファイルを簡単に導入でき、日本人向けに使いやすくしたものです。
 Twitter→ https://twitter.com/ai_nios/status/1617901380370587654 <br>
 note→　https://note.com/ai_nios/n/n0826a33edc8a<br>
 <br>
 2023/4/21 <br>
StableDiffusion webuiを無料で利用する場合、アカウントがBANされることはありませんが、Colabが一時的に利用できなくなる可能性があることが示唆されています。無料で実行する場合は、自己責任でお願いします。。<br>
Pro版の方は、今まで通り利用していただいて構いません<br>
[詳細](https://research.google.com/colaboratory/faq.html#limitations-and-restrictions)
## Colab
| Colab name | Colab Page |
| --- | --- |
Nios_Model_Card_Selection.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_Model_Card_Selection.ipynb)  
Nios_v2_update.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_v2_update.ipynb) 
Nios_v3.ipynb | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_v3.ipynb) 
Nios_v4_final.ipynb |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/stable-diffusion-webui-colab-japanese/blob/main/Nios_v4_final.ipynb) 

【推奨ブラウザ】PC:Chrome, Edge スマホ: googleアプリ, safari<br>

## 注意事項
###  生成した画像の利用については自己判断および自己責任でお願いします。

## Colab Pageの概要
### Nios_Model_Card_Selection.ipynb
使用方法:noteに記載 URL → https://note.com/ai_nios/n/n0826a33edc8a 
### Nios_v2_update.ipynb
より多くのcheckpointファイルを選択できます。
Nios_Model_Card_Selection.ipynbのプログラムコードに加え、公開されてる学習済みのLoRAやTextual InversionをColab上から選択してダウンロードできるプログラムコードを追加しています。<br>
ControlNetを使用できます。<br>
### Nios_v3.ipynb
https://github.com/camenduru/stable-diffusion-webui-colab のColabのソースコードに基づき、Nios_v2_update.ipynbと同じ感覚で使用できるようにしました。<br>
### Nios_v4_final.ipynb
より多くのモデルがダウンロード可能です。<br>
## 追加・変更のお知らせ
### 2023/02/05<br>
EasyNegative追加。ネガティブプロンプトにEasyNegativeといれることにより余計な否定プロンプトを書く必要がなくなりました。<br>
### 2023/02/10<br>
WebUI拡張機能 Aspect Ratio selectorの追加。画像のアスペクト比セレクターボタンを追加しました。 1:1,2:3,3:4,9:16など<br>
WebUI拡張機能 images-browserの追加。WebUI起動後から現在までに生成された画像を閲覧することができます。<br>
### 2023/02/18<br>
WebUI拡張機能 Push to 🤗 Hugging Faceの追加。WebUI上からモデルやVAE、LoRAを追加することができます。<br>
WebUI拡張機能 ControlNet追加しました。<br>
### 2023/03/06<br>
WebUI拡張機能 sd-webui-depth-lib追加<br>
WebUI拡張機能 stable-diffusion-webui-chatgpt-utilities追加（OpenAIの有料アカウントが必須）colabで使えた方は報告求む。<br>
### 2023/03/16<br>
Nios_v2_update.ipynb以降の仕様変更<br>
### 2023/03/28<br>
Colab上からモデルを追加できるようになりました。
### 2023/04/02<br>
プログラムを大幅に改善しました。
## 対応モデル名(Nios_v2_update.ipynb以降）<br>
### ckpt（safetensors）ファイル<br>
"stable_diffusion_v1.5","stable_diffusion_v2.1","waifu_diffusion_v1.3","Openjourney","anything-v3.0","anything-v4.0","anything-v4.5","Counterfeit-V2.0","Counterfeit-V2.5","8528-diffusion","AbyssOrangeMix2","EerieOrangeMix2","trinart2_step115000","Eimis Anime Diffusion_1.0v","dreamlike-photoreal-2.0","Cyberpunk-Anime-Diffusion","Plat Diffusion v1.3.1","ACertainThing","pastel_mix","Basil_mix_fixed","Realistic Vision V1.3","SukiyakiMix-v1.0","7th_anime_v1.1", "7th_anime_v2_A", "7th_anime_v2_B", "7th_anime_v2_C", "7th_anime_v2_G", "7th_anime_v3_A", "7th_anime_v3_B", "7th_anime_v3_C","7th_anime_3.1_B","YuzuGinger_v4","YuzuLemonMilk_v1.5", "Defmix-v1.1","RDtMix","meadmix","Nabylon-v1.0","LonganMix","Corneo's 7th Heaven Mix", "Corneo's Shinra26 Mix","atwmix_test2","Graham_Special", "BalorV2featAbyssOrange2","Balor-V2.5featAOM3A3","ChilloutMix", "wd-1-5-beta2"

## WebUI拡張機能(Extensions)
･[Stable Diffusion WebUI Aspect Ratio selector(アスペクト比セレクター)](https://github.com/alemeliTwitters/sd-webui-ar)<br>
･[stable-diffusion-webui-images-browser(イメージ ブラウザ)](https://github.com/yfszzx/stable-diffusion-webui-images-browser)<br>
･[Push to 🤗 Hugging Face](https://github.com/camenduru/stable-diffusion-webui-huggingface)<br>
･[Booru tag autocompletion for A1111(タグのオートコンプリート)](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)<br>
･[Dataset Tag Editor](https://github.com/toshiaki1729/stable-diffusion-webui-dataset-tag-editor)<br>
･[Merge Block Weighted - GUI](https://github.com/bbc-mc/sdweb-merge-block-weighted-gui)<br>
･[sd-civitai-browser](https://github.com/camenduru/sd-civitai-browser)<br>
･[Additional Networks for generating images](https://github.com/kohya-ss/sd-webui-additional-networks)<br>
･[Latent Couple extension (two shot diffusion port)](https://github.com/opparco/stable-diffusion-webui-two-shot)<br>
･[sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet)<br>
･[Openpose Editor](https://github.com/camenduru/openpose-editor)<br>
･[sd-webui-depth-lib](https://github.com/jexom/sd-webui-depth-lib)<br>
･[stable-diffusion-webui-chatgpt-utilities](https://github.com/hallatore/stable-diffusion-webui-chatgpt-utilities)（OpenAIの有料アカウントが必須）<br>
･[stable-diffusion-webui-rembg](https://github.com/AUTOMATIC1111/stable-diffusion-webui-rembg)<br>
･[batchlinks-webui](https://github.com/etherealxx/batchlinks-webui)<br>
･[sd-dynamic-prompts](https://github.com/adieyal/sd-dynamic-promp)<br>
･[a1111-sd-webui-locon](https://github.com/KohakuBlueleaf/a1111-sd-webui-locon)<br>
