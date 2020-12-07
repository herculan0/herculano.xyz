---
title: "Deploying an Hugo Website on Amazon S3 and Cloudfront using Terraform"
date: 2020-08-16
tags: ["AWS", "Hugo", "S3", "CloudFront"]
categories: ["Cloud Computing", "Blog", "Hugo", "AWS", "AWS S3"]
description: "Uma maneira fácil de fazer deploy de um Website feito com Hugo em um Bucket S3 usando Terraform. De quebra ainda vamos usar CloudFront pra entregar o conteúdo pelo mundo e o Certificate Manager da AWS"
draft: false
---

# Tô bem animado pra escrever meu primeiro tutorial no meu mais novo blog/terreno pessoal na interwebs. Sinta-se à vontade pra me dar um feedback ou mandar alguma sugestão de alteração.

Primeiro, vamos criar nosso website em Hugo e usar um tema pra ele ficar com algum estilo.

Obs: Se você não conhece o hugo ainda, visita o Quickstart deles, é bem maneiro e a documentação é bem sucinta e direta ao ponto [https://gohugo.io/getting-started/quick-start](Hugo Quickstart)

```
hugo new site hugo-aws-s3
cd hugo-aws-s3
git init
git submodule add https://github.com/J-Siu/hugo-theme-sk1.git themes/hugo-theme-sk1

```

Malesuada vel arcu odio scelerisque tellus adipiscing congue vitae erat leo commodo. Rhoncus amet cras curabitur non augue aenean eu nibh nisl orci lorem. Augue rhoncus euismod leo nam netus viverra interdum lectus do quam. Consequat dolor metus urna ultricies mi aliquet dolore dictum. Facilisi facilisis et eiusmod mus orci consectetur dolore ultricies placerat porttitor sed. Est labore hendrerit id malesuada interdum quisque mollis mattis ut.

Aliqua congue egestas bibendum pretium semper id vulputate eleifend lorem vestibulum auctor. Euismod eleifend eiusmod at vel suspendisse donec commodo sit volutpat do. Iaculis accimsan ipsum suscipit labore mattis sollicitudin sit eiusmod turpis. Nisi pulvinar vulputate scelerisque feugiat posuere a dui faucibus. Nam ultrices magnis netus sed faucibus aliqua interdum laoreet consectetur eleifend. Malesuada elit enim ullamcorper commodo eget pretium penatibus vitae vestibulum iaculis.
