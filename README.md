# 音声対話型検索における応答の長さとタスク複雑性に関する実験データ

##リポジトリ概要

本リポジトリは、DAWAK 2025で発表予定の以下の論文に基づき、実験で使用したデータを公開するものです。

**Ken Tobioka, Takehiro Yamamoto, and Hiroaki Ohshima**  
*Effects of Response Length on User Search Experience in Spoken Conversational Search*  
To appear in *Proceedings of the 27th International Conference on Big Data Analytics and Knowledge Discovery (DAWAK 2025)*.

また、重み付きナゲット再現率および情報獲得量の分析に使用したデータも含まれています。

##データ内容

- `conversation.csv`（`conversation.xlsx`）  
  ユーザとシステムの対話ログを記録したファイルです。

- `nuggets.csv`（`nuggets.xlsx`）  
  ユーザ要約ナゲットとシステム応答ナゲットを記載したファイルです。

- `llm-as-a-judge-prompt.ipynb`  
  GPT-4.1（2025-04-14）を用いてナゲット抽出を行った際のプロンプトを含むNotebookです。

##引用方法

本データを使用する際は、以下の論文を引用してください。

**Ken Tobioka, Takehiro Yamamoto, and Hiroaki Ohshima**  
*Effects of Response Length on User Search Experience in Spoken Conversational Search*  
To appear in *Proceedings of the 27th International Conference on Big Data Analytics and Knowledge Discovery (DAWAK 2025)*.

## 📬 お問い合わせ

兵庫県立大学 山本 岳洋  
Email: t.yamamoto@sis.u-hyogo.ac.jp

---

# Experimental Data on Response Length and Task Complexity in Spoken Conversational Search

##Repository Overview

This repository contains the experimental data used in the following paper:

**Ken Tobioka, Takehiro Yamamoto, and Hiroaki Ohshima**  
*Effects of Response Length on User Search Experience in Spoken Conversational Search*  
To appear in *Proceedings of the 27th International Conference on Big Data Analytics and Knowledge Discovery (DAWAK 2025)*.

It also includes the data used for the analysis of **weighted nugget recall** and **information acquisition**.

##Data Files

- `conversation.csv` (`conversation.xlsx`)  
  Contains the dialogues between users and the system during the spoken conversational search tasks.

- `nuggets.csv` (`nuggets.xlsx`)  
  Contains user summary nuggets and system response nuggets used for evaluation.

- `llm-as-a-judge-prompt.ipynb`  
  Provides the prompt used with GPT-4.1 (as of 2025-04-14) to extract nuggets under the LLM-as-a-Judge evaluation framework.

##How to Cite

If you use this dataset in your research, please cite the following paper:

**Ken Tobioka, Takehiro Yamamoto, and Hiroaki Ohshima**  
*Effects of Response Length on User Search Experience in Spoken Conversational Search*,  
To appear in *Proceedings of the 27th International Conference on Big Data Analytics and Knowledge Discovery (DAWAK 2025)*.

##Contact

Takehiro Yamamoto  
University of Hyogo  
Email: t.yamamoto@sis.u-hyogo.ac.jp
