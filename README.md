# UI-bookmarklet

## Description
This bookmarklet outlines all html elements on the website with different colors and shows the "id" and the "classes" of the hovered element. After refreshing the website it's back to normal.

## Usage
Add new bookmark and past the script from "prod" file in the "URL" field. Тhat's all.

### Enjoy!!!

# <a class="bookmarklet" href="javascript:(function()%7Blet%20body%20%3D%20document.getElementsByTagName('body')%5B0%5D%3Bif%20(body.outlined)%20%7Bbody.querySelectorAll('*').forEach(e%20%3D%3E%20e.style.outline%20%3D%20%22none%22)%3Bbody.outlined%20%3D%20false%3B%7D%20else%20%7Bconst%20tagProps%20%3D%20%7BDIV%3A%20%5B2%2C%20'double'%2C%20'%2303adfc'%5D%2CSPAN%3A%20%5B1%2C%20'double'%2C%20'%23ff0000'%5D%2CH1%3A%20%5B1%2C%20'dashed'%2C%20'%231e229c'%5D%2CH2%3A%20%5B1%2C%20'dashed'%2C%20'%231e229c'%5D%2CH3%3A%20%5B1%2C%20'dashed'%2C%20'%231e229c'%5D%2CH4%3A%20%5B1%2C%20'dashed'%2C%20'%231e229c'%5D%2CA%3A%20%5B2%2C%20'dotted'%2C%20'%23fc0362'%5D%2CINPUT%3A%20%5B2%2C%20'groove'%2C%20'%23ffff00'%5D%2CP%3A%20%5B2%2C%20'dashed'%2C%20'%23000000'%5D%2CUL%3A%20%5B2%2C%20'ridge'%2C%20'%23874040'%5D%2COL%3A%20%5B2%2C%20'ridge'%2C%20'%23874040'%5D%2CLI%3A%20%5B2%2C%20'ridge'%2C%20'%23874040'%5D%2CTABLE%3A%20%5B2%2C%20'ridge'%2C%20'%23bd27e3'%5D%2CTD%3A%20%5B2%2C%20'ridge'%2C%20'%23bd27e3'%5D%2CTH%3A%20%5B2%2C%20'ridge'%2C%20'%23bd27e3'%5D%2CIMG%3A%20%5B2%2C%20'double'%2C%20'%23ff0000'%5D%7D%3Bconst%20set%20%3D%20(el)%20%3D%3E%20%7Bel.style.outline%20%3D%20tagProps%5Bel.tagName%5D%20%3F%20%60%24%7BtagProps%5Bel.tagName%5D%5B0%5D%7Dpx%20%24%7BtagProps%5Bel.tagName%5D%5B1%5D%7D%20%24%7BtagProps%5Bel.tagName%5D%5B2%5D%7D%60%20%3A%20'1px%20dashed%20%23222'%3Bel.title%20%3D%20%60%24%7Bel.tagName%7D%20%24%7Bel.id%20%3F%20'id%3D'%20%2B%20el.id%20%3A%20''%7D%20%24%7Bel.className%20%3F%20'class%3D'%20%2B%20%20el.className%20%3A%20''%7D%60%3B%7D%3Bbody.querySelectorAll('*').forEach(el%20%3D%3E%20set(el))%3Bbody.outlined%20%3D%20true%3B%7D%7D)()" title="A  class=bookmarklet" style="outline: none;">show</a>
