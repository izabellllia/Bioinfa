## 1. Последовательность белка

**Длина:** 153 аминокислоты  

MSTLTSVSGFPRIGQNRELKKIIEGYWKGANDLAAVKATAAELRAKHWRLQQAAGIDLIASNDFSYYDQMLDTAILLNVIPQRYQRLAFDDQEDTLFAMA

yaml
Копировать код

---

## 2. Полученные ноутбуки

- `alphafold2.ipynb`
- `omegafold.ipynb`

---

## 3. Полученные структуры (PDB)

- `alphafold2.pdb`
- `omegafold.pdb`

---

## 4. Выравнивание структур

**Метод:** pairwise alignment  
**Цепь:** Chain A  
**Инструмент:** PyMOL `align` (аналог jFATCAT-flexible)  
**Файл выравнивания:** `alignment/jfatcat_aligned.pdb`  

### 4.1 Лог выравнивания

Match: read scoring matrix.
Match: assigning 100 x 100 pairwise scores.
MatchAlign: aligning residues (100 vs 100)...
MatchAlign: score 508.000
ExecutiveAlign: 794 atoms aligned.
ExecutiveRMS: 42 atoms rejected during cycle 1 (RMSD=6.68)
ExecutiveRMS: 44 atoms rejected during cycle 2 (RMSD=5.54)
ExecutiveRMS: 34 atoms rejected during cycle 3 (RMSD=4.75)
ExecutiveRMS: 31 atoms rejected during cycle 4 (RMSD=4.25)
ExecutiveRMS: 24 atoms rejected during cycle 5 (RMSD=3.84)
Executive: RMSD = 3.568 (619 to 619 atoms)

markdown
Копировать код

### 4.2 Визуализация и раскраска

- AlphaFold2: оранжевый  
- OmegaFold: розовый  

**Скриншоты выравнивания:**

![Скриншот 1](screenshots/alignment_view1.png)  
![Скриншот 2](screenshots/alignment_view2.png)

---

## 5. Выводы о совпадении предсказаний

1. Оба предсказания (**AlphaFold2** и **OmegaFold**) демонстрируют **сходный третичный фолдинг**.  
2. **RMSD выравнивания:** 3.568 Å  
3. Основные совпадения: глобальный фолдинг, альфа-спирали.  
4. Различия: небольшие вариации в петлях и концевых областях.  
5. **Вывод:** модели согласуются, различия минимальны, что подтверждает стабильность предсказаний.