import 'package:flutter/material.dart';
import 'package:table_calendar/table_calendar.dart';

class MyCalendar extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return TableCalendar(
      firstDay: DateTime.now().subtract(Duration(days: 365)),
      lastDay: DateTime.now().add(Duration(days: 365)),
      focusedDay: DateTime.now(),
      // Добавь обработчики для событий
    );
  }
} # -
