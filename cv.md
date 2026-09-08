# Uliana Kucherenko

**Front-end Developer**

* Bucharest, Romania  
* Phone: [+40 (775) 29 91 86](tel:+40775299186) 
* Email: [kucherenko.ul.ana@gmail.com](mailto:kucherenko.ul.ana@gmail.com)
* [LinkedIn](https://linkedin.com/in/uliana-kucherenko)
* [GitHub](https://github.com/UlyanaKucherenko)

## Profile

Front-end Developer with experience in React and Next.js. I focus on building responsive interfaces, working with APIs, and collaborating in international teams. I care about writing clean, maintainable code and continuous learning. I joined RS School to expand into Full-Stack development, explore new approaches, and refresh my knowledge of core theory.

## Skills

- **Core:** JavaScript (ES6+), TypeScript, HTML5, CSS3, React, Next.js
- **Styling:** SASS/SCSS, Styled-components, responsive layouts
- **Tools:** Git, GitLab, Jira, Figma, Chrome DevTools
- **Soft skills:** technical documentation, code review, teamwork and communication

## Code Examples

### JavaScript: sort numbers by the number of set bits

```javascript
function getBits(element) {
	const bits = element.toString(2);
	let bitCount = 0;

	for (let index = 0; index < bits.length; index += 1) {
		if (bits[index] === '1') bitCount += 1;
	}

	return bitCount;
}

function sortByBit(numbers) {
	numbers.sort((first, second) => {
		const firstBitCount = getBits(first);
		const secondBitCount = getBits(second);

		return firstBitCount === secondBitCount
			? first - second
			: firstBitCount - secondBitCount;
	});

	return numbers;
}

sortByBit([3, 8, 3, 6, 5, 7, 9, 1]);
// [1, 8, 3, 3, 5, 6, 9, 7]
```

## Work Experience

### Front-end Developer, TopDevs Inc, Ukraine

**March 2021 - May 2025**

#### Social network and streaming platform

A social network with streaming, user chat, posts, and multiple user roles, including an administrator role.

- Developed features for creating and viewing posts for different user roles, including administrators.
- Developed a notification system for chat and video calls, improving the product workflow.
- Contributed technical insights and solutions during team and client meetings.
- Optimized the codebase and improved application performance, efficiency, and reliability.

#### Educational platform

A web application where users can create personal accounts, download study materials, and subscribe to tariff plans.

- Developed the web version of the dashboard, improving its functionality and user experience.
- Led an API-first interface approach to support component development across teams.
- Integrated third-party APIs to extend application functionality.

## Education

### Bachelor of Computer Sciences

National University "Zaporizhzhia Polytechnic"  
**2016 - 2020**

### RS School. Fullstack Engineering Course

Starting intensive Full-Stack course covering TypeScript, React, Node.js, and collaborative project development.
## Language

- **Intermediate (B1).** I use English to communicate with international teams and clients and to read technical documentation.
- **Ukrainian - native** 
- **Russian - native** 