FROM tmvdl/kotlin

WORKDIR /app

COPY . .

RUN kotlinc ./Main.kt -include-runtime -d /app/Main.jar

RUN java -jar /app/Main.jar

CMD ls -la
