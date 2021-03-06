# Метрические пространства. Справочник.
## Термины

* Пространство называется **_метрическим_**, если на нём определена **_метрика_** - функция расстояния
  **_ρ: M × M → M_** такая, что:
    1. ρ(x, y) = 0 ⇔ x = y
    2. ρ(x, y) = ρ(y, x)
    3. ρ(x, y) ≤ ρ(x, z) + ρ(z, y) ∀x, y, z ∈ M
* **_δ-окрестностью_** точки **_a_** в метрических пространствах называют множество точек, находящихся
  от точки **_a_** на расстоянии, не превосходящем **_δ_**.
* Точка **_a_** называется **_внутренней_** точкой метрического множества _M_, если существует такая **_δ-окрестность_**
  точки **_a_**, что каждая точка этой окрестности так же содержится в метрическом множестве _M_.
* Множество _M_ называется **_открытым_**, если все его точки являются _внутренними_.
* Точка **_a_** называется **_предельной точкой_** множества _M_, если в любой её окрестности есть точка не из _M_.
  `!Предельная точка множества может не принадлежать самому множеству!`
* Точка **_a_** называется **_граничной_** точкой множества _M_, если в любой её окрестности есть как точки из _M_, так
  и точки не из _M_.
* Множество _M_ называется **_замкнутым_**, если оно содержит все свои **_предельные точки_**.
* Точка **_a_** множества _M_ называется **_изолированной_**, если у неё существует окрестность, не содержащая в _M_
  точек, отличных от **_a_**.
* **_Компакт_**:
    1. `В общем случае`: множество _M_ называется **_компактным_**, если из любой последовательности этого множества
        можно выделить сходящуюся в _M_ подпоследовательность.
    2. `Следствие на ℝ^n`: множество называется **_компактом_**, если оно **_ограниченно_** и **_замкнуто_**.
* Множество называется **_связным_**, если его _невозможно_ разбить на два _непустых непересекающихся открытых подмножества_.
