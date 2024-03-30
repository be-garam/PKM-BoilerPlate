# PKM-BoilerPlate
It's be-garam's personal boilerplate for PKM base on obsidian

## 소개
나는 항상 PKM 특히 제텔카스텐이 공부 및 지식을 아카이빙하는 용도에 맞게 변형시킬 수 있을까를 고민해왔다. 
- 틀릴 수도 있지만, 개인적으로 나에게 있어 제텔카스텐은 생산성에 치중되어 있는 내용으로 느껴졌기 때문이다. 

이에 나는 아래와 같은 아이디어를 가지고 해당 BoilerPlate를 만들게 되었다.
> 누군가도 어떤 책, 수업을 작성할 때, 자신이 가지고 있는 Knowledge, fleeting note에서 목적에 따라 하나의 글을 써내려간 것

즉, 해당하는 BoilerPlate는 다른 사람이 작성한 글을 기준으로 이 사람이 어떤 Base Knowledge를 가지고 있었는지를 마치 역기획하듯이 파헤치는 것에 초점을 맞춘다. 

## 파일 구조
```
├── .obsidian        
├── NoteName 
│       └── NoteName.md
│       └── Chapter{n}.md
├── Resource
│       └── Concept.md
├── Source
│       └── image.png(jpg)
└── Template
        └── Template for Resource.md
```

### .obsidian 
> obsidian을 기반으로 하였기 때문에, 개인적으로 세팅해둔 값이 들어가게 됩니다.
- [24.03.30] 아직 최적화 작업은 해두지 못했습니다.

### NoteName
> 정리의 대상인 폴더, 파일을 의미합니다. 


**NoteName.md**
- Chapter{n}.md 파일을 하나로 정리한 목차 같은 폴더 입니다.

**Chapter{n}.md**
- {Chapter_title}.md 형태로 바꾸어도 되며, 이 파일이 대상이 된 강의, 책, 글의 원문을 이해합니다. 
- 기본적인 골조로는 Resource 파일에 있는 개념을 가져와 해당하는 파일에서 연결성을 부여한다는 개념으로 가져가게 됩니다.

### Resource
> 개념들을 담아둔 폴더로, 각 파일들은 그 자체로 완전해야 합니다.

**Concept.md**
- 개념에 대해서 정리되어 있는 파일로 정형화된 구조를 따릅니다.([Template for Resource.md](./Template/Template for Resource.md))

### Source
> 모든 md 파일에 들어가는 이미지, 파일 소스들을 저장해두는 폴더입니다.

### Template
> Obsidian의 Template 기능을 활용하여 새로운 Resource 파일을 쉽게 생성할 수 있도록 돕습니다.  

- `cmd(ctrl) + p`를 통해 command line을 키고 `Templates: Insert template`를 사용하여 진행할 수 있습니다. 