# Multiplataforma_S6_L6
# ETHAN ARREDONDO 5-C24-B
import 'package:flutter/material.dart';
import 'package:flutter/widgets.dart';

void main() {
  runApp(MyApp());
}

// staless vs stalefull
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(home: HomePage());
  }
}

class HomePage extends StatefulWidget {
  @override
  State<HomePage> createState() => _HomePageState();
}

class _HomePageState extends State<HomePage> {
  int counter = 0;
  @override
  Widget build(BuildContext context) {
    return Expanded(
        child: Column(children: <Widget>[
      Expanded(
          child: Container(
              color: Color.fromARGB(255, 186, 208, 224),
              child: Row(
                mainAxisAlignment: MainAxisAlignment.center,
                children: const <Widget>[
                  Text("C    0    +",
                      style:
                          TextStyle(fontSize: 50, fontWeight: FontWeight.bold, color: Color.fromARGB(255, 0, 0, 0)))
                ],
              ))),
      Expanded(
          child: Container(
              color: Color.fromARGB(255, 186, 208, 224),
              child: Row(
                mainAxisAlignment: MainAxisAlignment.center,
                children:[
                  Text("1    2    3",
                      style:
                          TextStyle(fontSize: 50, fontWeight: FontWeight.bold, color: Color.fromARGB(255, 0, 0, 0)))
                ]
              ))),
      Expanded(
          child: Container(
              color: Color.fromARGB(255, 186, 208, 224),
              child: Row(
                mainAxisAlignment: MainAxisAlignment.center,
                children: const <Widget>[
                  Text("4    5    6",
                      style:
                          TextStyle(fontSize: 50, fontWeight: FontWeight.bold, color: Color.fromARGB(255, 0, 0, 0)))
                ],
              ))),
      Expanded(
          child: Container(
              color: Color.fromARGB(255, 186, 208, 224),
              child: Row(
                mainAxisAlignment: MainAxisAlignment.center,
                children: const <Widget>[
                  Text("7    8    9",
                      style:
                          TextStyle(fontSize: 50, fontWeight: FontWeight.bold, color: Color.fromARGB(255, 0, 0, 0)))
                ],
              ))),
        Expanded(
          child: Container(
              color: Color.fromARGB(255, 186, 208, 224),
              child: Row(
                mainAxisAlignment: MainAxisAlignment.center,
                children: const <Widget>[
                  Text("-    *    /",
                      style:
                          TextStyle(fontSize: 50, fontWeight: FontWeight.bold, color: Color.fromARGB(255, 0, 0, 0)))
                ],
              ))),  
    ]));
  }
}
