# Reporte de Análisis de Datos - Pandas

`Jaquez Andres Machine Learning pandas, NC 0074`

## 1. DataFrame Convertido
```text
  Hospital  Camas  Doctores
0  General    500       120
1     IMSS    300        80
2   ISSSTE    250        70
3    Civil    400       100
4  Militar    200        60
5  Privado    150        45
```

## 2.1 Primeras Filas (head)
```text
  Hospital  Camas  Doctores
0  General    500       120
1     IMSS    300        80
```

## 2.2 Últimas Filas (tail)
```text
  Hospital  Camas  Doctores
4  Militar    200        60
5  Privado    150        45
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Hospital      str
Camas       int64
Doctores    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column    Non-Null Count  Dtype
---  ------    --------------  -----
 0   Hospital  6 non-null      str  
 1   Camas     6 non-null      int64
 2   Doctores  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Camas'
```text
count      6.000000
mean     300.000000
std      130.384048
min      150.000000
25%      212.500000
50%      275.000000
75%      375.000000
max      500.000000
Name: Camas, dtype: float64
```

## 4. Ordenar Ascendente por Camas
```text
  Hospital  Camas  Doctores
5  Privado    150        45
4  Militar    200        60
2   ISSSTE    250        70
1     IMSS    300        80
3    Civil    400       100
0  General    500       120
```

## 5. Ordenar Descendente por Doctores
```text
  Hospital  Camas  Doctores
0  General    500       120
3    Civil    400       100
1     IMSS    300        80
2   ISSSTE    250        70
4  Militar    200        60
5  Privado    150        45
```

`Jaquez Andres Machine Learning pandas, NC 0074`