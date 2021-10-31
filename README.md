# Решение команды "Баден-Баден Баден-Баден"

Что происходит: в каждой из подпапок `chronom`, `chugun`, `gas`, `lomproduv`, `plavki` и `sip` есть скрипты, которые генерируют признаки. Эти скрипты запускаются в основном функцией `merge_data` в `plavki/pipeline.py`. Таким образом, чтобы повторить наши действия, нужно произвести следующие операции:

1. Сохранить все данные в папку `data`.
2. Запустить ноутбук `plavki/final_hope.ipynb`.
2. Запустить ноутбуки `gas/gas_autofeatures.ipynb` и `gas/gas_plus_chronom.ipynb`.
3. Запустить ноутбук `plavki/for_reproducing.ipynb`.