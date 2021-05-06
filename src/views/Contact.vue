<template>
<div id="contact-form" class="contact-form">
		<h1 class="contact-form_title">Contact Form</h1>
		<form class="form" @submit="onSubmit">
			<input required name="name" v-model='contact.name' placeholder="Name" type="text">
			<input required name="email" v-model="contact.email" placeholder="E-mail" type="email">
			<textarea name="message" v-model="contact.message" rows="4" placeholder="Message"></textarea>
		   <button class="button">Send</button>
		</form>
	</div>
</template>
