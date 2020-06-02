---
# SPDX-FileCopyrightText: © 2018 Martin Michlmayr <tbm@cyrius.com>
#
# SPDX-License-Identifier: GPL-3.0-or-later
title: ledger2beancount
subtitle: Ledger to Beancount converter
author:
    - Stefano Zacchiroli
    - Martin Michlmayr
keywords: ledger, beancount, conversion, accounting, bookkeeping
date: June 2020
documentclass: scrartcl
urlcolor: blue
toc: true
---

# ledger2beancount

[ledger2beancount](https://github.com/zacchiro/ledger2beancount/) is a
script to automatically convert [Ledger](https://www.ledger-cli.org/)-based
textual ledgers to [Beancount](http://furius.ca/beancount/) ones.

Conversion is based on (concrete) syntax, so that information that is not
meaningful for accounting reasons but still valuable (e.g., comments,
formatting, etc.) can be preserved.

ledger2beancount aims to be compatible with the latest official release of
beancount.
