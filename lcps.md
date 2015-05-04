# Изучение паралельных вычислений на Scala

## Глоссарий

- Concurrent Programming - Параллельные вычисления

test test test
test test
~~Mistaken text.~~

test *test* test dfgdgd dfgdfgdf sddndarj **sfsdfs** sdfgjsigoj
sdfsdfkosdkfo  fdgkdfhkdohkdgokho

```scala
import scala.io.Source
object FuturesDataType extends App {
  val buildFile: Future[String] = Future {
    val f = Source.fromFile("build.sbt")
    try f.getLines.mkString("\n") finally f.close()
  }
  log(s"started reading the build file asynchronously")
  log(s"status: ${buildFile.isCompleted}")
  Thread.sleep(250)
  log(s"status: ${buildFile.isCompleted}")
  log(s"value: ${buildFile.value}")
}
```

sdfsdfsdfvrtretertbvcb  dggerger
er
gergggrega fdkgakldfgakg `dgfdfgdfg` dfgdfgdsgdsdfsdfhsgfjs

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
