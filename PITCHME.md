### Continuous Integration and Deployment

Upscale by GOJEK

#HSLIDE

- Graduated not long ago
- Graduated Gojek Engineering Bootcamp 2
- Gopay International Product Engineer
![](assets/bootcamp.jpeg)

#HSLIDE

#### Whats interesting from Gopay International

Part of Gojek History

#HSLIDE

```
Mas, can you help me, this customer getting error bla bla bla bla bla bla
```

#HSLIDE

to this
```
Mas can you help me, this customer getting error
```

![](assets/error.png)

#HSLIDE

#### Review time

![](assets/will.jpg)

#HSLIDE

What is
#### Devops?

#HSLIDE

What hold us(engineer) deliver our features?

#HSLIDE

Analyze -> Code(unit test included) -> Deploy Staging -> Test -> Deploy Production

#HSLIDE

#### Simple? No!!

#HSLIDE

- Red code on staging.
- excuses on `it is working on my local env`
- and other silly excuse

#HSLIDE

#### Gitlab CI CD
![](assets/cicd.png)

#HSLIDE
```yaml
image: jruby:9.1.6

stages:
  - a

step_a:
  stage: a
  script:
    - echo "hai"
    
```

#HSLIDE
[gitlab.com/blfsh/rails-ci](https://gitlab.com/blfsh/rails-ci)
