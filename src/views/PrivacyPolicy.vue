<template>
  <div class="container mx-auto py-12 text-primary font-sans">
    <section class="py-12">
      <h1 class="text-5xl font-bold mb-6 animate-fadeIn">GDPR Privacy Statement</h1>
      <div class="space-y-4 animate-fadeIn">
        <p>
          This privacy statement sets out how Ballyheigue Community Centre uses and protects any information that you provide us with when you use this website. By registering or placing a donation on this website, you consent to the collection, use and transfer of your information under the terms of this statement.
        </p>
        <p>
          Ballyheigue Community Centre will endeavor to ensure that your privacy is protected and acts in accordance with the Data Protection Acts 1988 – 2003. If we ask you to provide certain information by which you can be identified when using this website then you can be assured that it will only be used in accordance with this privacy statement.
        </p>
        <p>
          Ballyheigue Community Centre may change this statement from time to time by updating this page. You should review this page regularly so that you will always be aware of what information we collect, how it is used and under what circumstances, if any, we share it with other parties.
        </p>
        <h2 class="text-2xl font-bold mt-6">What we collect</h2>
        <p>We may collect the following information:</p>
        <ul class="list-disc list-inside">
          <li>Name</li>
          <li>Contact information including email address</li>
        </ul>
        <h2 class="text-2xl font-bold mt-6">What we do with the information we gather</h2>
        <p>
          We require this information to understand your needs and provide you with a better service, and in particular for the following reasons:
        </p>
        <ul class="list-disc list-inside">
          <li>To improve our services</li>
          <li>To contact you if you have given us permission to do so, e.g. newsletters.</li>
        </ul>
        <h2 class="text-2xl font-bold mt-6">Cookies</h2>
        <p>
          This website uses "cookies" technology. A cookie is a piece of text stored by the browser on your computer, at the request of our server. We may use cookies to deliver content specific to your interests and to save your personal preferences so that you do not have to re-enter them each time that you connect to our website. You are always free to decline our cookies, if your browser permits, or to ask your browser to indicate when a cookie is being sent. You can also delete cookie files from your computer at your discretion. Note that if you decline our cookies or ask for notification each time a cookie is being sent, this may restrict your ease of use of this website.
        </p>
        <h2 class="text-2xl font-bold mt-6">Security</h2>
        <p>
          We take our responsibilities in relation to the security of your Personal Data very seriously. The nature of the internet is such that we cannot guarantee or warrant the security of any information you transmit to us via the internet. No data transmission over the internet can be guaranteed to be 100% secure. However, we will take all reasonable steps (including appropriate technical and organisational measures) to protect your Personal Data and we will review these measures regularly.
        </p>
        <h2 class="text-2xl font-bold mt-6">Links to other websites</h2>
        <p>
          Our website may contain links to other websites of interest. However, once you use these links to leave our site, you should note that we do not have any control over that other website. Therefore, we cannot be responsible for the protection and privacy of any information which you provide whilst visiting such sites and such sites are not governed by this privacy statement. You should exercise caution and look at the privacy statement applicable to the website in question.
        </p>
        <h2 class="text-2xl font-bold mt-6">Controlling your personal information</h2>
        <p>
          Ballyheigue Community Centre does not collect any personal data about you on this website, apart from the information that you volunteer (for example by e-mailing us, by using our online Contact Us form or providing information in connection with a donation). Any personal information which you provide in this way is not made available to any third party, other than as required by law, and is used by Ballyheigue Community Centre only in line with the purpose(s) for which you provided it.
        </p>
        <p>
          You may request details of personal information which we hold about you under the Data Protection Acts 1988 – 2003. A small fee will be payable. If you would like a copy of the information held on you please write to Ballyheigue Community Centre, Ballyheigue, Co. Kerry.
        </p>
        <p>
          If you believe that any information we are holding on you is incorrect or incomplete, please write to us at the above address or email us at <a href="mailto:info@ballyheiguecommunitycentre.ie" class="text-green-500 hover:underline">info@ballyheiguecommunitycentre.ie</a>, as soon as possible. We will promptly correct any information found to be incorrect.
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'PrivacyPolicy'
};
</script>

<style scoped>
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.animate-fadeIn {
  animation: fadeIn 1s ease-in-out;
}

.text-primary {
  color: #333;
}

.text-secondary {
  color: #555;
}

.text-green-500 {
  color: #48bb78;
}

.hover\:underline:hover {
  text-decoration: underline;
}
</style>
