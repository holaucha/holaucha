``` abap
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2//EN">
<html>
<head>
<title>SAPMZ00_C616_TOP</title>
</head>
<body bgcolor="#FFFFE0">
<font size="3" face = "Arial" color="#000000"><b>Code listing for: SAPMZ00_C616_TOP</b></font>
<br>
<font size="3" face = "Arial" color="#000000"><b>Description:  Include SAPMZ00_C616_TOP</b></font>
<hr>
<pre width="100">
<font color ="#0000FF">*&---------------------------------------------------------------------*</font>
<font color ="#0000FF">*& Include SAPMZ00_C616_TOP                         - Module Pool      SAPMZ00_C616</font>
<font color ="#0000FF">*&---------------------------------------------------------------------*</font>
PROGRAM sapmz00_c616.

TABLES: scarr, spfli.

DATA: ok_code     TYPE sy-ucomm,
      gv_rb01     VALUE 'X',
      gv_rb02,
      gv_rb03,
      gv_url      TYPE scarr-url,
      gv_carrid   TYPE scarr-carrid,
      gv_selid    TYPE scarr-carrid,
      gv_ckb01(1) TYPE c,
      gs_scarr    TYPE scarr,
      gs_spfli    TYPE spfli.

CONSTANTS marked VALUE 'X'.
