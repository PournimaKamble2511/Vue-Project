<template>
        <footer data-w-id="1356e90d-e3a3-2953-9ae6-a897ae2f46c5" class="footer">
        <div class="container-main">
            <div class="w-layout-grid footer-grid">
                <div data-w-id="860ef3f3-f653-7152-d923-41d83ef45dfc" class="links-block link-address">
                    <div class="footer-links-title">
                        <h3 class="footer-title">COMPANY<span class="dropdown-icon-footer"></span></h3>
                    </div>
                    <div class="footer-links-wrapper footer-links-wrapper-new">
                        <p class="paragraph-white in-footer">
                            4275 Executive Sq
                            <br>
                            La Jolla, CA 92037
                            <br>
                            United States
                        </p>
                        <ul role="list" class="footer-links-list w-list-unstyled d-desktop-menu">
                            <li class="footer-link-item">
                            <a :href="contactUsUrl" class="footer-link">Contact Us</a>
                            </li> 
                        </ul>
                        <ul role="list" class="footer-links-list w-list-unstyled d-mob-menu">
                            <li class="footer-link-item">
                                <asp:HyperLink runat="server" Target="_blank" ID="hyperLinkLearningHub1" class="footer-link"
                                    NavigateUrl="~/learning-hub">Learning Hub</asp:HyperLink>
                            </li>
                            <li class="footer-link-item">
                                <asp:HyperLink runat="server" ID="hyperLinkJoinUs1"
                                    data-w-id="dcbcff1b-b540-5f88-0e1d-5bee92257871" class="footer-link" NavigateUrl="#">
                                    Join Us</asp:HyperLink>
                            </li>
                            <li class="footer-link-item">
                                <asp:HyperLink runat="server" ID="hyperLinkContactUS1" class="footer-link"
                                    NavigateUrl="~/contact-us">
                                    Contact Us
                                </asp:HyperLink>
                            </li>

                        </ul>
                    </div>
                </div>
                <div class="links-block">
                    <div class="footer-links-title">
                        <h3 class="footer-title">TOP CATEGORIES<span class="dropdown-icon-footer"></span></h3>
                    </div>
                    <div class="footer-links-wrapper footer-links-wrapper-new">
                        <ul role="list" class="footer-links-list w-list-unstyled">
                            <li class="footer-link-item">
                                <a :href="MarketingUrl" Target="_blank" class="footer-link">Marketing</a>
                            </li>
                            <li class="footer-link-item">
                                <a :href="TechnologyUrl" Target="_blank" class="footer-link">Technology</a>
                            </li>
                            <li class="footer-link-item">
                                 <a :href="HumanResourcesUrl" Target="_blank" class="footer-link">Human Resources</a>
                            </li>
                            <li class="footer-link-item">
                            <a :href="FinanceUrl" Target="_blank" class="footer-link">Finance</a>
                            </li>
                            <li class="footer-link-item">
                                <a :href="HealthcareUrl" class="footer-link w-inline-block" target="_blank">Healthcare</a>
                            </li>
                        </ul>
                        <ul role="list" class="footer-links-list w-list-unstyled d-desktop-menu">
                            <li class="footer-link-item">
                                    <a :href="LearningHubUrl" Target="_blank" class="footer-link">Learning Hub</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="links-block">
                    <div class="footer-links-title">
                        <h3 class="footer-title">community<span class="dropdown-icon-footer"></span></h3>
                    </div>
                    <div class="footer-links-wrapper footer-links-wrapper-new">
                        <ul role="list" class="footer-links-list w-list-unstyled">
                            <li class="footer-link-item">
                                    <a :href="organizersUrl" Target="_blank" class="footer-link">Organizers</a>
                            </li>
                            <li class="footer-link-item">
                                    <a :href="sponsorsUrl" Target="_blank" class="footer-link">Sponsors</a>
                            </li>
                            <li class="footer-link-item">
                                    <a :href="speakersUrl" Target="_blank" class="footer-link">Speakers</a>
                            </li>
                            <li class="footer-link-item">
                                <a :href="suppliersUrl" Target="_blank" class="footer-link">Suppliers</a>
                            </li>
                        </ul>
                        <ul role="list" class="footer-links-list w-list-unstyled d-desktop-menu">
                             <li class="footer-link-item">
                                    <a :href="joinUsUrl" data-w-id="dcbcff1b-b540-5f88-0e1d-5bee92257871" class="footer-link">Join Us</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="links-block">
                    <div class="footer-links-title">
                        <h3 class="footer-title">Policies<span class="dropdown-icon-footer"></span></h3>
                    </div>
                    <div class="footer-links-wrapper footer-links-wrapper-new">
                        <ul role="list" class="footer-links-list w-list-unstyled">
                            <li class="footer-link-item">
                                    <a :href="privacyPolicyUrl" class="footer-link"  Target="_blank">Privacy Policy</a>
                            </li>
                            <li class="footer-link-item">
                                    <a :href="termsofUseUrl" class="footer-link" Target="_blank">Terms of Use</a>
                            </li>
                            <li class="footer-link-item">
                                <a :href="communityGuidelinesUrl" class="footer-link" Target="_blank">Community Guidelines</a>
                            </li>
                            <li class="footer-link-item">
                            <a :href="contentUsageGuidelinesUrl" class="footer-link" Target="_blank">Content Usage Guidelines</a>

                        </li>
                        <li class="footer-link-item">
                                <a :href="legalUrl" class="footer-link" Target="_blank">Legal</a>
                        </li>

                    </ul>
                </div>
            </div>   
        </div>
        <div class="footer-bottom">
                        <div class="footer-bottom-left">
                            <a href="/" aria-current="page" class="brand w-nav-brand w--current">
                                <img src="https://eventually.com/images/logo-white.svg" loading="lazy" alt="" class="footer-logo">
                            </a>
                        </div>
                        <div class="footer-bottom-right">
                            <div class="footer-social-links-wrapper">
                                <a href="https://www.linkedin.com/company/eventuallydotcom" target="_blank" class="footer-social-media-link-wrapper w-inline-block" rel="nofollow">
                                    <div></div>
                                </a>
                                <a href="https://www.facebook.com/eventuallydotcom" target="_blank" class="footer-social-media-link-wrapper w-inline-block" rel="nofollow">
                                    <div></div>
                                </a>
                                <a href="https://twitter.com/eventually_com" target="_blank" class="footer-social-media-link-wrapper w-inline-block" rel="nofollow">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900.03 920.47" width="17" height="17" fill="#B5BBBF">

                                        <g id="Layer_2" data-name="Layer 2">
                                            <g id="Layer_1-2" data-name="Layer 1">
                                                <path d="M870.83,0Q797.11,85.88,723.38,171.76,632.6,277.36,541.74,382.9c-1.75,2-3.43,4.13-5.75,6.92L900,919.64c-3.27.29-5.46.65-7.66.65q-126.25,0-252.5.18c-5.92,0-9-2.11-12.2-6.76Q510.63,743,393.29,572.47c-2-2.9-4.08-5.75-6.59-9.28-22.89,26.58-45.16,52.42-67.4,78.27Q201.83,778,84.2,914.45a18.06,18.06,0,0,1-11.87,5.61c-23.32.53-46.65.26-72.33.26L351.35,511.88c-1.72-2.66-3.23-5.15-4.88-7.54Q176.89,257.49,7.31,10.63C5,7.22,3,3.55.85,0H268.67a42.12,42.12,0,0,0,2.13,3.9Q383.92,168.58,497.05,333.24c1.12,1.63,2,3.46,3.15,5.58L791.75,0ZM108.18,59.65c3,4.39,4.87,7.3,6.86,10.14q38.84,55.56,77.7,111.11Q428.6,518.32,664.37,855.81c3.6,5.16,7.2,7.54,13.75,7.48,34.44-.35,68.88-.15,103.31-.19,2.78,0,5.55-.33,9.54-.59-2.8-4.17-4.71-7.12-6.72-10q-197.8-283-395.61-565.91-76.91-110-154-219.9c-2.22-3.16-6.68-6.69-10.14-6.74C186.47,59.47,148.45,59.65,108.18,59.65Z" />
                                            </g>
                                        </g>
                                    </svg>
                                </a>
                                <a href="https://www.instagram.com/eventuallydotcom/?hl=en" target="_blank" class="footer-social-media-link-wrapper w-inline-block" rel="nofollow">
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="35" height="35" viewBox="0 0 64 64" style="fill: #B5BBBF;">
                                        <path d="M 31.820312 12 C 13.439312 12 12 13.439312 12 31.820312 L 12 32.179688 C 12 50.560688 13.439312 52 31.820312 52 L 32.179688 52 C 50.560688 52 52 50.560688 52 32.179688 L 52 32 C 52 13.452 50.548 12 32 12 L 31.820312 12 z M 28 16 L 36 16 C 47.129 16 48 16.871 48 28 L 48 36 C 48 47.129 47.129 48 36 48 L 28 48 C 16.871 48 16 47.129 16 36 L 16 28 C 16 16.871 16.871 16 28 16 z M 41.994141 20 C 40.889141 20.003 39.997 20.900859 40 22.005859 C 40.003 23.110859 40.900859 24.003 42.005859 24 C 43.110859 23.997 44.003 23.099141 44 21.994141 C 43.997 20.889141 43.099141 19.997 41.994141 20 z M 31.976562 22 C 26.454563 22.013 21.987 26.501437 22 32.023438 C 22.013 37.545437 26.501437 42.013 32.023438 42 C 37.545437 41.987 42.013 37.498562 42 31.976562 C 41.987 26.454563 37.498562 21.987 31.976562 22 z M 31.986328 26 C 35.299328 25.992 37.992 28.673328 38 31.986328 C 38.007 35.299328 35.326672 37.992 32.013672 38 C 28.700672 38.008 26.008 35.327672 26 32.013672 C 25.992 28.700672 28.673328 26.008 31.986328 26 z"></path>
                                    </svg>
                                </a>
                            </div>
                            <div data-w-id="76ca228a-f8f3-30dc-0a18-ad54764b64fe" class="privacy-links-wrapper margin-top-24">
                                <div class="mouse-print">
                                    <a href="https://eventually.com/terms-of-use" target="_blank" class="link-2">Terms of Use</a> | <a href="https://eventually.com/privacy-policy" target="_blank" class="link-2">Privacy Policy</a> | © eventually.com
             
                                </div>
                            </div>
                        </div>
                    </div>
    
    </div>
</footer>

</template>

<script setup>
const contactUsUrl = 'https://eventually.com/contact-us';
const MarketingUrl = 'https://eventually.com/category/marketing-and-advertising';
const TechnologyUrl = 'https://eventually.com/category/information-technology';
const HumanResourcesUrl = 'https://eventually.com/category/human-resources';
const FinanceUrl = 'https://eventually.com/category/finance';
const HealthcareUrl = 'https://eventually.com/category/healthcare';
const LearningHubUrl = 'https://eventually.com/learning-hub';
const organizersUrl = 'https://eventually.com/organizers';
const sponsorsUrl = 'https://eventually.com/sponsors';
const speakersUrl = 'https://eventually.com/speakers';
const suppliersUrl = 'https://eventually.com/suppliers';
const joinUsUrl = '#';
const privacyPolicyUrl = 'https://eventually.com/privacy-policy';
const termsofUseUrl = 'https://eventually.com/terms-of-use';
const communityGuidelinesUrl = 'https://eventually.com/community-guidelines';
const contentUsageGuidelinesUrl = 'https://eventually.com/content-usage-guidelines';
const legalUrl = 'https://eventually.com/legal';

</script>

<style scoped>

</style>