```js
import { Temmy, Bio } from "portfolio"

class AboutMe extends Temmy.Bio {
  const getTemmyKnowledge = () => {
    return (
		[
		    id: 1, name: 'UI',
		    id: 2, name: 'UX',
		    id: 3, name: 'Design System',
		    id: 4, name: 'HTML & CSS'
		 ]
	   )
     }
     
    render (
      return (
	 <div>
	    {getTemmyKnowledge().map(item => {
		return(
		  {item.id} {item.name}
		)
	    })}
	 </div>
	)
    )
}

export default AboutMe
```

### Hey y'all, I'm TEMMY! Since 2017, I've been living and breathing design. As of now, out here designing modern user interfaces and looking for partner to colaborate with me. 👋 
Currently living in Japan 🇯🇵 and have an eligible visa (JP Spouse Visa) to be able to work in various fields of work. 

<!--
**bytemmy/bytemmy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
