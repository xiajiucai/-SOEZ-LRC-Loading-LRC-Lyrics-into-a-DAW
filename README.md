# SOEZ-LRC Plugin

[中文](#lang-cn) ｜ [English](#lang-en) ｜ [日本語](#lang-jp) ｜ [한국어](#lang-kr)

---

<a id="lang-cn"></a>

## SOEZ-LRC Plugin（中文）

这是一个多功能用途并加载在DAW中加载LRC用于录音翻唱等多功能用途的歌词加载插件，内含四语言设置（默认中文），包含局域网预览歌词，这款插件是基于 [JUCE9] 开发的 VST3 插件。使用时请遵守当前开源协议 **GNU Affero General Public License v3.0**。目前开发版本持续更新中，有任何 bug 和任何想法欢迎反馈。

### 使用说明

**目录：**
- [基础介绍](#cn-基础介绍)
- [导入](#cn-导入)
- [起点定位](#cn-起点定位)
- [延迟调整](#cn-延迟调整)
- [跟随（原始LRC歌词时间）](#cn-跟随原始lrc歌词时间)
- [局域网功能](#cn-局域网功能)
- [高亮颜色设置](#cn-高亮颜色设置)
- [语言设置](#cn-语言设置)
- [清空歌词](#cn-清空歌词)

<a id="cn-基础介绍"></a>
#### 基础介绍

该插件可以让你在 DAW（Digital Audio Workstation，支持 VST3 插件的宿主软件）中加载，并提供类似 QQ 音乐或 Apple Music 的歌词页面，让你轻松翻唱歌曲、录音、舞台演出时查看歌词的多功能工具。支持四国语言设置：中文、英文、日文、韩文。同时拥有局域网共享功能，让你或者现场的朋友使用平板、手机等智能设备，只需扫描二维码（QR码）或复制插件局域网的链接，即可打开局域网页面实时查看歌词。支持自定义个性化歌词高亮颜色，可以实时编辑歌词内容，自动跟随存档，与你的 DAW 工程文件一起存入工程数据，下次打开无需重新导入与设置。

<a id="cn-导入"></a>
#### 导入

安装完插件后，请确保你的宿主软件（DAW: Digital Audio Workstation）已扫描到该插件（SOEZ-LRC）。

加载插件后主界面如图所示。可以拖拽、点击、右键导入你制作好的 LRC 歌词来进行加载。

[图文编号-C01]

<a id="cn-起点定位"></a>
#### 起点定位

加载歌词完毕后，需要手动定位你当前音频文件或者你当前歌词文件的开头位置，如图 [图文编号-C02]。这样可以保证你播放音频时歌词 100% 同步上。

<a id="cn-延迟调整"></a>
#### 延迟调整

如果发现点击「起点」定位后依然存在一些延迟，可以点击 **+10ms** 或 **-10ms** 来调整延迟时间 [图文编号-C03]，也可以通过拖动滑块或者双击延迟时间进行手动输入延迟设置 [图文编号-C04]。如果你发现滑块调整过度或者想要恢复 0s 的延迟调整，双击滑块即可复位为 0。

<a id="cn-跟随原始lrc歌词时间"></a>
#### 跟随（原始LRC歌词时间）

如果你想让 LRC 从头最初开始、按原始的 LRC 时间进行播放歌词预览，点击「跟随」按钮即可让它恢复全局，如图 [图文编号-C05]。

<a id="cn-局域网功能"></a>
#### 局域网功能

局域网共享功能，能让你或者现场的朋友使用平板、手机等智能设备、电脑来进行局域网连接或开放端口映射远程连接。只需要扫描二维码（QR码）或复制插件局域网的链接，即可打开局域网页面来实时查看歌词 [图文编号-C06]。独立网页设置四国语言，独立设备延迟调整，可以随时校准；插件和局域网都可以缩放歌词大小 [图文编号-C07]。

<a id="cn-高亮颜色设置"></a>
#### 高亮颜色设置

点击左上角的颜色，或者右键呼出菜单中的「修改歌词颜色」，即可修改歌词的高亮颜色（默认为白色高亮）[图文编号-C08]。

<a id="cn-语言设置"></a>
#### 语言设置

点击「语言：你设置的语言」即可调整其他语言设置 [图文编号-C09]。初始语言与局域网同步语言，但提供独立的局域网语言修改设置 [图文编号-C10]。

<a id="cn-清空歌词"></a>
#### 清空歌词

点击「清空」即可清除当前加载的歌词。如图 [图文编号-C11]。

[⬆ 返回顶部](#soez-lrc-plugin)

---

<a id="lang-en"></a>

## SOEZ-LRC Plugin (English)

This is a multi-purpose lyrics loading plugin that loads LRC files in a DAW for recording, cover singing, and other purposes. It includes four language settings (Chinese by default) and supports LAN lyrics preview. It is a VST3 plugin developed based on [JUCE9]. When using it, please comply with the current open-source license, **GNU Affero General Public License v3.0**. The development version is continuously being updated. Any bugs or ideas are welcome for feedback.

### User Guide

**Table of Contents:**
- [Basic Introduction](#en-basic-introduction)
- [Import](#en-import)
- [Start-Point Positioning](#en-start-point-positioning)
- [Delay Adjustment](#en-delay-adjustment)
- [Follow (Original LRC Lyrics Time)](#en-follow-original-lrc-lyrics-time)
- [LAN Function](#en-lan-function)
- [Highlight Color Settings](#en-highlight-color-settings)
- [Language Settings](#en-language-settings)
- [Clear Lyrics](#en-clear-lyrics)

<a id="en-basic-introduction"></a>
#### Basic Introduction

This plugin can be loaded into a DAW (Digital Audio Workstation that supports VST3 plugins) and provides a lyrics page similar to QQ Music or Apple Music. It is a multi-purpose tool that lets you easily record cover songs, and view lyrics during recording or live stage performances. It supports four languages: Chinese, English, Japanese, and Korean. It also features LAN sharing: you or your friends on site can use tablets, phones, or other smart devices — just scan the QR code or copy the plugin's LAN link to open the LAN page and view lyrics in real time. It supports customizable lyric highlight colors, real-time lyric editing, and auto-follow saving — lyrics are stored with your DAW project data, so no re-importing or reconfiguring is needed next time you open it.

<a id="en-import"></a>
#### Import

After installing the plugin, make sure your host software (DAW: Digital Audio Workstation) has scanned the plugin (SOEZ-LRC).

After loading the plugin, the main interface is shown below. You can drag, click, or right-click to import the LRC lyrics you have created.

[Image No.-E01]

<a id="en-start-point-positioning"></a>
#### Start-Point Positioning

After loading the lyrics, you need to manually position the beginning of your current audio file or lyrics file, as shown in [Image No.-E02]. This ensures the lyrics are 100% synced when you play the audio.

<a id="en-delay-adjustment"></a>
#### Delay Adjustment

If you still notice some delay after clicking "Start Point", you can click **+10ms** or **-10ms** to adjust the delay time [Image No.-E03]. You can also drag the slider or double-click the delay time to manually enter a delay value [Image No.-E04]. If you've over-adjusted the slider or want to restore the 0s delay, simply double-click the slider to reset it to 0.

<a id="en-follow-original-lrc-lyrics-time"></a>
#### Follow (Original LRC Lyrics Time)

If you want the lyrics preview to start from the very beginning using the original LRC timing, click the "Follow" button to restore it globally, as shown in [Image No.-E05].

<a id="en-lan-function"></a>
#### LAN Function

The LAN sharing feature lets you or your friends on site use tablets, phones, other smart devices, or computers to connect over the LAN or via open port mapping for remote connections. Just scan the QR code or copy the plugin's LAN link to open the LAN page and view lyrics in real time [Image No.-E06]. The standalone web page supports four language settings and per-device delay adjustment that can be calibrated at any time. Both the plugin and the LAN page allow you to scale the lyric size [Image No.-E07].

<a id="en-highlight-color-settings"></a>
#### Highlight Color Settings

Click the color in the upper-left corner, or use "Edit Lyrics Color" in the right-click menu to change the lyric highlight color (default is white highlight) [Image No.-E08].

<a id="en-language-settings"></a>
#### Language Settings

Click "Language: your current language" to adjust other language settings [Image No.-E09]. The initial language is synced with the LAN language, but a separate LAN language setting is also provided [Image No.-E10].

<a id="en-clear-lyrics"></a>
#### Clear Lyrics

Click "Clear" to remove the currently loaded lyrics. As shown in [Image No.-E11].

[⬆ Back to top](#soez-lrc-plugin)

---

<a id="lang-jp"></a>

## SOEZ-LRC Plugin（日本語）

これは多機能な歌詞読み込みプラグインで、DAW で LRC を読み込み、録音やカバー歌唱など多目的に使用できます。4 言語設定（デフォルトは中国語）を備え、LAN 経由の歌詞プレビューに対応しています。JUCE9 をベースに開発された VST3 プラグインです。使用時は現在のオープンソースライセンス **GNU Affero General Public License v3.0** を遵守してください。開発版は継続的に更新中です。バグやアイデアがあれば、ぜひフィードバックをお寄せください。

### 使用方法

**目次：**
- [基本紹介](#jp-基本紹介)
- [読み込み](#jp-読み込み)
- [開始位置の指定](#jp-開始位置の指定)
- [遅延調整](#jp-遅延調整)
- [フォロー（元のLRC歌詞タイム）](#jp-フォロー元のlrc歌詞タイム)
- [LAN機能](#jp-lan機能)
- [ハイライト色の設定](#jp-ハイライト色の設定)
- [言語設定](#jp-言語設定)
- [歌詞のクリア](#jp-歌詞のクリア)

<a id="jp-基本紹介"></a>
#### 基本紹介

このプラグインは、DAW（デジタルオーディオワークステーション、VST3 プラグイン対応）に読み込んで、QQ 音楽や Apple Music のような歌詞ページを表示できる多機能ツールです。カバー歌唱の録音やステージ演奏時に歌詞を確認するのに便利です。4 言語設定（中国語、英語、日本語、韓国語）を備えています。さらに LAN 共有機能があり、ご本人や会場の友人がタブレット、スマートフォンなどのスマートデバイスで、QR コードをスキャンするかプラグインの LAN リンクをコピーするだけで LAN ページを開き、リアルタイムで歌詞を表示できます。歌詞のハイライト色をカスタマイズでき、歌詞内容をリアルタイムで編集でき、自動保存により DAW プロジェクトファイルと一緒にプロジェクトデータに保存されるため、次回開く際に再読み込みや再設定は不要です。

<a id="jp-読み込み"></a>
#### 読み込み

プラグインをインストールした後、ホストソフト（DAW: デジタルオーディオワークステーション）がプラグイン（SOEZ-LRC）をスキャン済みであることを確認してください。

プラグインを読み込んだ後のメイン画面は次のとおりです。ドラッグ、クリック、右クリックメニューからインポートして、作成した LRC 歌詞を読み込めます。

[画像番号-J01]

<a id="jp-開始位置の指定"></a>
#### 開始位置の指定

歌詞を読み込んだ後、現在のオーディオファイルまたは歌詞ファイルの先頭位置を手動で指定する必要があります。[画像番号-J02] のとおりです。これにより、オーディオ再生時に歌詞が 100% 同期されます。

<a id="jp-遅延調整"></a>
#### 遅延調整

「開始位置」を指定した後も遅延が残る場合は、**+10ms** または **-10ms** をクリックして遅延時間を調整できます [画像番号-J03]。また、スライダーをドラッグするか、遅延時間をダブルクリックして手動で遅延設定を入力することもできます [画像番号-J04]。スライダーを調整しすぎた場合や 0s の遅延に戻したい場合は、スライダーをダブルクリックすると 0 にリセットされます。

<a id="jp-フォロー元のlrc歌詞タイム"></a>
#### フォロー（元のLRC歌詞タイム）

LRC を最初から元の LRC 時間で歌詞プレビューを再生したい場合は、「フォロー」ボタンをクリックするとグローバルに戻ります。[画像番号-J05] のとおりです。

<a id="jp-lan機能"></a>
#### LAN機能

LAN 共有機能により、ご本人や会場の友人がタブレット、スマートフォン、その他のスマートデバイス、パソコンで LAN 接続またはポートマッピングを開放してリモート接続できます。QR コードをスキャンするかプラグインの LAN リンクをコピーするだけで、LAN ページを開いてリアルタイムで歌詞を表示できます [画像番号-J06]。独立した Web ページで 4 言語設定、デバイスごとの遅延調整が可能で、いつでもキャリブレーションできます。プラグインと LAN ページの両方で歌詞サイズを拡大縮小できます [画像番号-J07]。

<a id="jp-ハイライト色の設定"></a>
#### ハイライト色の設定

左上の色をクリックするか、右クリックメニューの「歌詞の色を変更」をクリックすると、歌詞のハイライト色を変更できます（デフォルトは白いハイライト）[画像番号-J08]。

<a id="jp-言語設定"></a>
#### 言語設定

「言語：設定中の言語」をクリックすると、他の言語設定を調整できます [画像番号-J09]。初期言語は LAN 言語と同期しますが、独立した LAN 言語変更設定も用意されています [画像番号-J10]。

<a id="jp-歌詞のクリア"></a>
#### 歌詞のクリア

「クリア」をクリックすると、現在読み込まれている歌詞を消去できます。[画像番号-J11] のとおりです。

[⬆ トップへ戻る](#soez-lrc-plugin)

---

<a id="lang-kr"></a>

## SOEZ-LRC Plugin (한국어)

이것은 다목적 가사 로딩 플러그인으로, DAW에서 LRC를 로드하여 녹음, 커버 녹음 등 다양한 용도로 사용할 수 있습니다. 4개 언어 설정(기본값 중국어)이 포함되어 있으며 LAN 가사 미리보기를 지원합니다. JUCE9 기반으로 개발된 VST3 플러그인입니다. 사용 시 현재 오픈 소스 라이선스인 **GNU Affero General Public License v3.0**을 준수해 주세요. 개발 버전은 지속적으로 업데이트 중입니다. 버그나 아이디어가 있으면 언제든지 피드백을 환영합니다.

### 사용 설명

**목차:**
- [기본 소개](#kr-기본-소개)
- [가져오기](#kr-가져오기)
- [시작점 지정](#kr-시작점-지정)
- [지연 조정](#kr-지연-조정)
- [팔로우(원본 LRC 가사 시간)](#kr-팔로우원본-lrc-가사-시간)
- [LAN 기능](#kr-lan-기능)
- [하이라이트 색상 설정](#kr-하이라이트-색상-설정)
- [언어 설정](#kr-언어-설정)
- [가사 지우기](#kr-가사-지우기)

<a id="kr-기본-소개"></a>
#### 기본 소개

이 플러그인은 DAW(디지털 오디오 워크스테이션, VST3 플러그인 지원)에 로드하여 QQ뮤직이나 Apple Music처럼 가사 페이지를 표시할 수 있는 다기능 도구입니다. 커버 녹음이나 무대 공연 시 가사를 확인하기 편리합니다. 4개 언어 설정(중국어, 영어, 일본어, 한국어)을 지원합니다. 또한 LAN 공유 기능이 있어 본인이나 현장의 친구가 태블릿, 스마트폰 등 스마트 기기에서 QR 코드를 스캔하거나 플러그인의 LAN 링크를 복사하기만 하면 LAN 페이지를 열어 실시간으로 가사를 볼 수 있습니다. 가사 하이라이트 색상을 사용자 지정할 수 있고, 가사 내용을 실시간으로 편집할 수 있으며, 자동 저장되어 DAW 프로젝트 파일과 함께 프로젝트 데이터에 저장되므로 다음에 열 때 다시 가져오거나 설정할 필요가 없습니다.

<a id="kr-가져오기"></a>
#### 가져오기

플러그인을 설치한 후 호스트 소프트웨어(DAW: 디지털 오디오 워크스테이션)가 해당 플러그인(SOEZ-LRC)을 스캔했는지 확인하세요.

플러그인을 로드한 후 메인 화면은 다음과 같습니다. 드래그, 클릭, 우클릭 메뉴에서 가져오기를 통해 제작한 LRC 가사를 로드할 수 있습니다.

[이미지 번호-K01]

<a id="kr-시작점-지정"></a>
#### 시작점 지정

가사를 로드한 후 현재 오디오 파일 또는 가사 파일의 시작 위치를 수동으로 지정해야 합니다. [이미지 번호-K02]와 같습니다. 이렇게 하면 오디오 재생 시 가사가 100% 동기화됩니다.

<a id="kr-지연-조정"></a>
#### 지연 조정

"시작점"을 지정한 후에도 지연이 남아 있다면 **+10ms** 또는 **-10ms**를 클릭하여 지연 시간을 조정할 수 있습니다 [이미지 번호-K03]. 슬라이더를 드래그하거나 지연 시간을 더블클릭하여 수동으로 지연 설정을 입력할 수도 있습니다 [이미지 번호-K04]. 슬라이더를 과도하게 조정했거나 0s 지연으로 되돌리고 싶다면 슬라이더를 더블클릭하면 0으로 초기화됩니다.

<a id="kr-팔로우원본-lrc-가사-시간"></a>
#### 팔로우(원본 LRC 가사 시간)

LRC를 처음부터 원본 LRC 시간으로 가사 미리보기를 재생하고 싶다면 "팔로우" 버튼을 클릭하면 전역으로 복원됩니다. [이미지 번호-K05]와 같습니다.

<a id="kr-lan-기능"></a>
#### LAN 기능

LAN 공유 기능을 통해 본인이나 현장의 친구가 태블릿, 스마트폰, 기타 스마트 기기, 컴퓨터로 LAN 연결 또는 포트 매핑을 열어 원격 연결할 수 있습니다. QR 코드를 스캔하거나 플러그인의 LAN 링크를 복사하기만 하면 LAN 페이지를 열어 실시간으로 가사를 볼 수 있습니다 [이미지 번호-K06]. 독립 웹 페이지에서 4개 언어 설정, 기기별 지연 조정이 가능하며 언제든지 캘리브레이션할 수 있습니다. 플러그인과 LAN 페이지 모두에서 가사 크기를 조정할 수 있습니다 [이미지 번호-K07].

<a id="kr-하이라이트-색상-설정"></a>
#### 하이라이트 색상 설정

왼쪽 상단의 색상을 클릭하거나 우클릭 메뉴에서 "가사 색상 변경"을 클릭하면 가사 하이라이트 색상을 변경할 수 있습니다(기본값은 흰색 하이라이트) [이미지 번호-K08].

<a id="kr-언어-설정"></a>
#### 언어 설정

"언어: 설정된 언어"를 클릭하면 다른 언어 설정을 조정할 수 있습니다 [이미지 번호-K09]. 초기 언어는 LAN 언어와 동기화되지만 독립적인 LAN 언어 변경 설정도 제공됩니다 [이미지 번호-K10].

<a id="kr-가사-지우기"></a>
#### 가사 지우기

"지우기"를 클릭하면 현재 로드된 가사를 지울 수 있습니다. [이미지 번호-K11]과 같습니다.

[⬆ 맨 위로](#soez-lrc-plugin)

---

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0** — see the [LICENSE](LICENSE) file for details.
