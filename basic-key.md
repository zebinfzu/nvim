# vim基础快捷键

## important 01

### 认识vim的模式

1. normal
2. insert
3. visual
4. command

### 重要快捷键

1. normal hjkl(左下上右)
2. n -> insert 
  1. i 光标后插入
  2. a 光标后插入
3. i -> normal
  1. <ESC>
  2. ctrl+[ ->(改建) jj 
4. normal -> command模式(通过在normal模式下输入:)

## important 02

> blank字符: 空格 换行 回车
1. move(normal模式)
  1. 行首
    - 0 数字0 移动当本行行首
    - ^ 本行第一个不是blank字符的位置 改键 shift+h(大写H)
  2. 行尾
    - $
    - g_ 本行最后一个不是blank字符的位置 改键 shift+l(大写L)
2. n -> i
  1. 行首 I
  2. 行尾 A
  3. 行前 O
  4. 行后 o
3. 复制当前行 yy
4. 删除当前行 dd
5. 粘贴   p