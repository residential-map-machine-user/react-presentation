UdacityでReact Trainingコースを受けてみた
Note:
Remember to explain why it's for everyone: no sign-up, nothing to install.
Just MD. Then git-commit.

---

Reactのコンポジションについて

エンジニアが何かのメソッドを作る時と同様にUIを作成できる。
```
function ProfilePic(username){
  return (<img alt={username} src="https://github.com/" + username + ".png?size=200"/>)
}

function profilePic(username){
  return https://github.com/" + username + ".png?size=200
}
```

---

Reactのデータバインディングについて
データバインディングとは
>>  データに変更があった時に自動的にその変化を検知してアクションすること

--- 

命令的が宣言的か
- [ ] 車に乗っていて40度の車だったら、自分で温度を低くするようにノブを回す
- [ ] 車に乗っていて、40度の車で人が乗っていたら自動的に快適な温度にする

コードレベルで見るとどうなるのか?
```
const people = ['Amanda', 'Geoff', 'Michael', 'Richard', 'Ryan', 'Tyler']
const excitedPeople = []

//命令的
for (let i = 0; i < people.length; i++) {
    excitedPeople[i] = people[i] + '!'
}

//宣言的
const excitedPeople = people.map(name => name + '!')
```
---

