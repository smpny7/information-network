---
title: '情報ネットワーク論 予習課題4'
author: 'IKEDA Kaito'
date: \the\year/\the\month/\the\day
---

# Ethernet アドレス (MACアドレス) とは何ですか．

計算機の製造時に割り当てられる 6octet の識別子であり，世界中の全機器に重複せず割当てられている．


# IP アドレスとは何ですか．

ホストのネットワークインタフェースを一意に識別する32ビットの番号であり，8ビット毎の10進数をドットで区切って表現されている．


# Ethernet アドレスと IP アドレスの果たす役割の違いについて説明してください．

Ethernet アドレスは機器ごとに唯一性があるため，機器の識別に使うことができる．
IPアドレスはネットワーク上の階層に依存するため，機器の識別には使えないがそのネットワークインタフェースを識別することができる．


# IPアドレスにおけるネットマスクとは何ですか．ネットマスクが必要な理由を説明してください．

ネットマスクとは，IP アドレスのネットワーク部とホスト部を識別するための数値であり，
あるIPアドレスが自身と同じサブネットに属しているかどうかを判断するために使われる．


# ARP プロトコルとは何ですか．ARP プロトコルの必要な理由を説明してください．

送信先の計算機の MAC アドレスをブロードキャストして尋ねるためのプロトコルが ARP プロトコルであり，
ARP テーブルに使う MAC アドレスと IP アドレスの対応表を作成するためにこのプロトコルが用いられる．