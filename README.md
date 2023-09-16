# Scaffold-Widget-AppBar-Body-Bottom-Navigation-Floating-Action-and-Persistent-Footer--drawer
 import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      theme: ThemeData(brightness: Brightness.light),
      darkTheme: ThemeData(brightness: Brightness.dark),
      themeMode: ThemeMode.system,
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(
          title: Center(child: Text("Khadim Hussain")),
        ),
        floatingActionButton: FloatingActionButton(
          child: Icon(Icons.add),
          onPressed: () {},
        ),
        backgroundColor: Colors.yellowAccent,
        drawer: Drawer(
          child: Text('myapp'),
        ),
        body: Material(
          child: Center(
            child: Text("this is boday",
                style: TextStyle(
                    backgroundColor: Colors.green,
                    fontSize: 12,
                    color: Colors.white,
                    fontWeight: FontWeight.bold,
                    fontStyle: FontStyle.italic,
                    letterSpacing: 12,
                    wordSpacing: 2.3,
                    textBaseline: TextBaseline.alphabetic,
                    height: 4,
                    leadingDistribution: TextLeadingDistribution.proportional,
                    locale: Locale.fromSubtags(),
                    decoration: TextDecoration.overline,
                    decorationColor: Color(3))),
          ),
        ),
      ),
    ),
  );
}
