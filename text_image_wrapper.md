## HTML

```html
<div class="a_bit_about_me_wrapper">
    <img src="https://benaharoni.com/sites/default/files/inline-images/ben_aharoni_modern_hebrew_tutor_1_0_0.jpg" class="a_bit_about_me_image" alt="בן אהרוני">
    <div class="a_bit_about_me_text">
        <p>
            <strong>שלום ונעים מאד.</strong><br>
            <strong>שמי בן אהרוני.</strong><br>
        </p>
        <p>
            <strong>אני איש שיווק באינטרנט מומחה קידום אורגני.&nbsp;</strong>
        </p>
        <p>
            <strong>אני נטורופת מומחה לפסוריאזיס.&nbsp;</strong>
        </p>
        <p>
            <strong>אני מורה לשפות אנגלית ותאית.&nbsp;</strong>
        </p>
        <p>
            <strong>אני יועץ רילוקיישן לדרום מזרח אסיה.</strong>
        </p>
    </div>
</div>
````

## CSS

```css
/* a bit about me and image block */

.a_bit_about_me_wrapper {
	display: block;
	box-sizing: border-box;
	padding: var(--majoris);
}

.a_bit_about_me_image {
	margin-bottom: var(--majoris);
}

.a_bit_about_me_text {
	padding: var(--majoris);
	background: whitesmoke;
}

@media screen and (min-width: 999px) {
	.a_bit_about_me_wrapper {
		display: flex;
		justify-content: space-around;
		align-items: center;
	}

	.a_bit_about_me_image {
		width: 50%;
		height: 500px;
		margin-bottom: 0;
	}

	.a_bit_about_me_text {
		width: 50%;
		height: 500px;
	}

}
```
