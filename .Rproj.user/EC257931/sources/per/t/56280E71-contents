Scan()->X
data.frame(x,x,x)->s

#ayuda
help(mean)
?mean
help.search("median")
#tipo de datos 
doub<-4
doub=4 

doub

int = as.integer(3)
int

logi=FALSE
logi

char1="hola"
char1

char2<-"5+6"
char2

typeof(doub)
typeof(int)
typeof(char1)

2^3
9/6 
9%%6

a=2+2 # resultado de 2+2 se asigna a la variable a
b=3*2 # resultado de 3*2 se asigna a la variable b
b-a->c # resultado de b-a se asigna a la variable c

a
b
c

a==5
a==4 & b<2
a==4 | b<2
a==4 | b<2 & c !=
#vectores
vec=c(1, 3, 14)
vec
#marices
mat1 <- matrix(c(1,2,3,4,5,6), nrow = 2, ncol = 3) # por defecto las matrices se completan por columna
mat1

mat2 <- matrix(c(1,2,3,4,5,6), nrow = 2, ncol = 3, byrow = TRUE) # byrow = TRUE indica que complete la matriz por filas
mat

#array
arr <- array(c(1,2,3,4,5,6,7,8), dim = c(2,2,2))
arr
#matrices
m <- matrix(c(1,1,2,1),2,2)
m

#factores y factores ordenados
fac <- factor(c('H','M','M','H','H','M'), levels = c('H','M'))
ord <- ordered(c(1,2,1,2,3,1,2,1,2), levels = c(1,2,3))

ord <- ordered(c(1,2,1,2,3,1,2,1,2), levels = c(1,2,3))
ord2 <- ordered(c(1,2,1,2,3,1,2,1,2), levels = c(2,3,1))
ord3 <- ordered(c(1,2,1,2,3,1,2,1,2), levels = c(3,1,2))

fac <- factor(c('H','M','M','H','H','M'), levels = c('H','M'))
fac2 <- factor(c('H','M','M','H','H','M'), levels = c('M','H'))

#data frames y listas 
a <- c(1,5,4)
b <- c("hola", "adios", "hasta luego")
c <- c(TRUE, FALSE, FALSE)
d <- c(1,2,3,4,5)
dataframe <- data.frame(a, b, c)
dataframe

list1 <- list(a, b, c)
list1

list2 <- list(a, b, c, d)
list2

#aceso a los elementos de las estructuras de datos
vec <- c(1, 3, 14)
vec[3]

mat1 <- matrix(c(1,2,3,4,5,6), nrow = 2, ncol = 3)
mat1

mat1[2, 3]

arr <- array(c(1,2,3,4,5,6,7,8), dim = c(2,2,2)) # el ultimo 2 indica que son dos matrices

arr[2, 1, 2] # el elemento de la segunda fila primera columna de la segunda matriz

mat1[c(1,2), 3] # los elementos (1, 3) y (2, 3) de l

mat1[1,]

mat1[, c(1,2)]

dataframe$a
dataframe$a[1]
dataframe[1,]
list1[[2]]
list2[[4]][2]


#Ejemplos
peso <- c(19,14,15,17,20,23,30,19,25)
peso < 20
peso < 20 | peso > 25
peso[peso < 20]
peso[peso < 20 & peso != 15]
trat <- c(rep("A", 3), rep("B", 3), rep("C", 3))
peso[trat == "A"]
peso[trat == "A" | trat == "B"]
split(peso, trat)
split(peso, trat)$A
x <- 1:15; length(x)

y <- matrix(5, nrow = 3, ncol = 4); dim(y)
is.vector(x); is.vector(y); is.array(x)
x1 <- 1:5; x2 <- c(1, 2, 3, 4, 5); x3 <- "patata" > typeof(x1); typeof(x2); typeof(x3)
mode(x); mode(y); z <- c(TRUE, FALSE); mode(z)
attributes(y)
w <- list(a = 1:3, b = 5); attributes(w)
y <- as.data.frame(y); attributes(y)

#Ejemplos: Generaci?n de secuencias
x <- c(1, 2, 3, 4, 5)
x <- 1 : 10 ; y <- -5 : 3
1 : 4 + 1; 1 : (4 + 1)
x <- seq(from = 2, to = 18, by = 2) # la function seq genera una secuencia
x <- seq(from = 2, to = 18, length = 30)
y <- seq(along = x)
z <- c(1 : 5, 7:10, seq(from=-7, to=5, by=2))
rep(1, 5) #repite el 1 cinco veces
x <- 1:3; rep(x, 2)
y <- rep(5, 3); rep(x, y)
rep(1 : 3, rep(5, 3))
rep(x, x)
rep(x, length = 8)
gl(3, 5) # es equivalente a rep(1:3, rep(5, 3))
gl(4, 1, length = 20) # gl genera factores
gl(3, 4, label = c("Rubio", "Moreno", "Pelirrojo"))
     
     
#Ejemplos: Selecci?n de los elementos de un vector
x <- 1:7; x[1]; x[3]; x[c(2,6)] # el ; separa instrucciones
x[x > 4]
x > 4
y <- x > 4
x[y]
x[-c(1, 5)]; y <- c(1, 2, 6); x[y]
names(x) <- c("a", "b", "c", "d", "e", "manzana") # Cuidado con las dobles las comillas (tecla del 2)
x[c("a", "e", "manzana")]

#Ejemplos. Ordenaci?n de vectores
x <- c(7, 4, 5, 9, 1)
order(x)
sort(x)
rev(x)
rank(x)
x[order(x)]
y <- c(1, 5, 5, 5, 7, 7, 9, 9, 9, 9); rank(x, y)
min(x); which.min(x); which(x == min(x))
y <- c(1, 1, 2, 2, 3); order(y, x)


#Ejemplos de vectores de caracteres
paste1 <- paste(c("I", "J", "M"), 3:5, sep = "")
paste2 <- paste(c("I", "J", "M"), 3:5, sep = ".")
unir1 <- paste(c("el", "sol", "brilla"), collapse =" ")
unir2 <- paste(c("el", "sol", "brilla"), collapse ="-")
unir3 <- paste(c("el", "sol", "brilla"))
letras <- LETTERS[1:9]; n?meros <- 7:15
unir4 <- paste(letras, n?meros, sep ="")
substr("abcdef", 2, 4)
x <- paste(LETTERS[1:7], collapse = "")
substr(x, 3, 7) <- c("xyz")
x <- c(60, 90, 903); y <- factor(x); x ; y
as.numeric(as.character(y)) # convierte un vector factor en num?rico
factor1 <- factor(c("alto", "bajo", "medio"))
factor2 <- factor(c("alto", "bajo", "medio"), levels = c("bajo", "medio", "alto")) # cambia el orden de las etiquetas


#Ejemplos de arrays y matrices
a <- 1:24; dim(a) <- c(3,4,2)
arr1 <- array(7, dim = c(4,5))
mat1 <- matrix(10:29, nrow = 5)
mat2 <- matrix(10:29, nrow = 5, byrow = TRUE)
mat3 <- 10:29; dim(mat3) <- c(5, 4)
a[1,1,1]; a[1,1,2]; a[3,4,2]
a[2, , ] # es un array de dimensi?n c(4,2)
a[,3 , ] # es un array de dimensi?n c(3,2)
mat3[1, ]; mat3[, 2]; mat3[c(1, 3), c(2, 4)]
mat4 <- matrix(c(1, 3, 2, 4), nrow = 2); mat4
mat3[mat4] # coordenadas matricialmente
m1 <- matrix(1: 4, nr = 2, nc = 2)
m2 <- matrix(6: 9, nr = 2, nc = 2)
rbind(m1, m2) # rbind une matrices por filas
cbind(m1, m2) # cbind une matrices por columnas
diag(m1) # diagonal principal de la matriz

#Ejemplos de Data frames y listas
x <- 1:4; n <- 10; M <- c(10, 35); y <- 2:5 ; x; n; M; y
data.frame(x, n)
data.frame(x, M)
data.frame(x, y)
l1 <- list(x, y); l2 <- list(A = x, B = y) ; l1; l2
names(l1)
names(l2)
     