---
title: 第一章
description: 第一章練習測試
---

## Ex 1.1

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: f334cc4f8d
```

指派數值

`@instructions`
讓對象`x`等於`5`

`@hint`
使用`<-`

`@pre_exercise_code`

```{r}
y <- 3
```

`@sample_code`

```{r}
#讓對象x等於5
```

`@solution`

```{r}
x <- 5
```

`@sct`

```{r}
test_error()
test_object("x",
            undefined_msg = "請確認您給予`x`數值!",
            incorrect_msg = "你確定你給`x`的數值 !")
success_msg("恭喜您答對了")
```
