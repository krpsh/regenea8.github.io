---
layout: post
title: JSP Template
description: "JSP 템플릿"
modified: 2017-04-04
tags: [HTML, JSP, Template]
categories: [JSP]
image:
    feature: feature.jpg
    credit: dargadgetz
    creditlink: http://www.dargadgetz.com/ios-8-abstract-wallpaper-pack-for-iphone-5s-5c-and-ipod-touch-retina/
---

Java Web Application 를 제작하기 위해서는 JSP 파일을 생성해야 하는데요.
생성할 때 마다 기본 틀을 수정하려면 매우 번거롭습니다.
JSP Template 을 수정하면 이러한 번거로움을 줄일 수 있습니다.

`Window - Preferences`로 접근합니다.
![preview](https://regenea8.github.io/resources/images/jsp-template/1.png)

좌측 상단에 `jsp`를 검색하고 `Web - JSP Files - Editor - Templates`를 클릭합니다.
`New JSP File (html)`을 클릭합니다.
`Edit`를 클릭합니다.
![preview](https://regenea8.github.io/resources/images/jsp-template/2.png)

해당 위치에 아래의 소스를 복사 붙여넣기 합니다.
![preview](https://regenea8.github.io/resources/images/jsp-template/3.png)

### JSP Template

```HTML
<%@ page contentType="text/html; charset=UTF-8"%>
<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt"%>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta charset="UTF-8">
<title>Insert title here</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

</head>
<body>



</body>
</html>
```
`OK`를 클릭하고 빠져나옵니다.
![preview](https://regenea8.github.io/resources/images/jsp-template/4.png)

JSP 파일을 새로 생성하면 저장한 Template로 생성되는 것을 확인할 수 있습니다.
![preview](https://regenea8.github.io/resources/images/jsp-template/5.png)
