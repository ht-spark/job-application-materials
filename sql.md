## 1.常用NULL函数

### 1）nullif(a,b)

* a、b相等则为null，不等取a
* **常用于防止除数取0**

### 2）ifnull(expr1,expr2)

* 如果 `expr1` 是 `NULL` → 返回 `expr2`
* 如果 `expr1` 不是 `NULL` → 返回 `expr1`

## 2.case when

CASE
  WHEN 条件1 THEN 结果1
  WHEN 条件2 THEN 结果2
  WHEN 条件3 THEN 结果3
  ELSE 默认结果
END

## 3.coalesce

`COALESCE(a, b, ...)` ,返回第一个非`NULL`的值

## 4.转义符

![1790228829891](image/sql/1790228829891.png)
