``` abap
*&---------------------------------------------------------------------*
*& Include SAPMZ00_C616_TOP                         - Module Pool      SAPMZ00_C616
*&---------------------------------------------------------------------*
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

----------------------------------------------------------------------------------
Extracted by Direct Download Enterprise version 1.3.1 - E.G.Mellodew. 1998-2005 UK. Sap Release 758

