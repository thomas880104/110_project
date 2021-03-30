執行archive/menu_eng.py 或 archive/menu_TW.py
至少需要安裝之模組：
tensorflow               2.2.0
sounddevice              0.3.14
matplotlib               2.1.2
numpy                    1.17.0
pygame                   1.9.6


wav_to_npz.py 需將錄製的wav檔分為test,train,validation後，即可寫入npz檔
training_model.py 是將上方的npz檔訓練成model