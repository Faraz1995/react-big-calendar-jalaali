# React Big Calendar with Jalaali and Shamsi Support

This repository is a fork of [amirhsobhi/react-big-calendar-jalaali](https://github.com/amirhsobhi/react-big-calendar-jalaali) and is inspired by [FullCalendar](http://fullcalendar.io/). It extends the original project by adding full support for **Jalaali** and **Shamsi** calendars.

## Features

- **Jalaali and Shamsi Calendar Support**: Fully compatible with Jalaali (Persian) and Shamsi (Solar Hijri) calendars.
- **React Big Calendar Integration**: Built on top of the popular `react-big-calendar` library.
- **Easy to Use**: Simply pass the `useJalaali` prop to enable Jalaali/Shamsi calendar support.

## Usage

To enable Jalaali/Shamsi support, pass the `useJalaali` prop to the calendar component:

```jsx
import React from 'react';
import { Calendar } from 'your-package-name';

function MyCalendar() {
  return (
    <Calendar
      useJalaali
      events={[
        // Your events here
      ]}
    />
  );
}

export default MyCalendar;
