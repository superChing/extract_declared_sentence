extract_declared_sentence
=========================
抽取宣告刑。

**usage example:** `python3 extract_declared_sentence.py <directory or file path>`

**output example:**
[
   "file name", 
   {
      "accused": [
         [
            "charge", 
            "sentence"
         ],
         ...
      ]
      ...
   }
   ...
]         
統計：
{'accused_extraction_fail': 4,
 'doc': 991,
 'output': 75,
 'table': 2146,
 'table_format_exception': 164,
 'table_processing_fail': 166}

75個doc有結果
2146個table裡有166個table無法處理。