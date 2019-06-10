# THIS IS THE DOCUMENTAION FOR FRONT-END OF MYPUSTAK.COM
### This Application in build using Recat js . You need to have react in installed to run on your local system.
## HERE IS THE FULL FILE STRUCTURE(EXCLUDING THE node modules,build)

├── package.json
├── package-lock.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── manifest.json
│   ├── Mypustakfavicon.ico
│   ├── mypustak icon new.png
│   └── sitemap.xml
├── sitemap-builder.js
└── src
    ├── actions
    │   ├── accountAction.1.js
    │   ├── accountAction.js
    │   ├── addressAction.js
    │   ├── backendBookInventoryActions.js
    │   ├── backendConfirmOrderAction.js
    │   ├── BackenddonationActions.js
    │   ├── BackendorderAction.js
    │   ├── backendUpdateTRandBarcode.js
    │   ├── backendWalletActions.js
    │   ├── backofficedonationtrackinggetAction.js
    │   ├── backofficeorderdetailsAction.js
    │   ├── backofficewalletsearchAction.js
    │   ├── backofficeWalletUpdateActions.js
    │   ├── booksActions.js
    │   ├── cartAction.js
    │   ├── dataentrysalebydaterangeAction.js
    │   ├── donationActions.js
    │   ├── faqAction.js
    │   ├── homeAction.js
    │   ├── mailAcctions.js
    │   ├── orderAction.js
    │   ├── passbookAction.js
    │   ├── productAction.js
    │   ├── prouddonarAction.js
    │   ├── seodataAction.js
    │   ├── totalsalefilterAction.js
    │   ├── types.js
    │   ├── walletAction.js
    │   └── wishlistAction.js
    ├── actions.zip
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── books.json
    ├── change
    ├── components
    │   ├── Ask
    │   ├── BackOffice
    │   │   ├── BackOffice.js
    │   │   ├── BackOfficeLogin.css
    │   │   ├── BackOfficeLogin.js
    │   │   ├── backofficeWalletUpdate.js
    │   │   ├── dataentrysalebydaterange.js
    │   │   ├── OldBackOffice.js
    │   │   └── totalsalefilter.js
    │   ├── BookInventoryPage
    │   │   ├── BookInventoryDiv.js
    │   │   ├── BookInventoryHead.js
    │   │   ├── donation.css
    │   │   └── index.js
    │   ├── Cart
    │   │   ├── CartAddUserAddress.js
    │   │   ├── cart.css
    │   │   ├── Cart_img
    │   │   │   ├── book.jpg
    │   │   │   └── ThankYou.png
    │   │   ├── Cart.js
    │   │   ├── CartThanks.css
    │   │   ├── CartThanks.js
    │   │   └── CartUEditAddress.js
    │   ├── contact.css
    │   ├── Contact.js
    │   ├── ConvProceedToPay.js
    │   ├── delivery
    │   │   ├── AddAddress.js
    │   │   ├── address.css
    │   │   ├── AddUserAddress.js
    │   │   ├── Delivery.js
    │   │   ├── InputGroup.css
    │   │   ├── InputGroup.js
    │   │   ├── oLD_AddUserAddress.js
    │   │   ├── OldPramodaddress.css
    │   │   ├── OldPramodDelivery.js
    │   │   ├── old_UEditAddress.js
    │   │   ├── old_UserInputGroup.js
    │   │   ├── UEditAddress.js
    │   │   ├── useraddress.css
    │   │   ├── usereditaddress.css
    │   │   └── UserInputGroup.js
    │   ├── DonationForm
    │   │   ├── form
    │   │   │   ├── AirTelMoney.png
    │   │   │   ├── Amazon_Pay.png
    │   │   │   ├── button.css
    │   │   │   ├── Button.js
    │   │   │   ├── calender.png
    │   │   │   ├── Cash_On_delivery.png
    │   │   │   ├── debit_&_credit_card.png
    │   │   │   ├── Donationform.css
    │   │   │   ├── Donationform.js
    │   │   │   ├── DonationPickup.css
    │   │   │   ├── DonationPickup.js
    │   │   │   ├── Error.js
    │   │   │   ├── FreeCharge.png
    │   │   │   ├── hand_icon.jpg
    │   │   │   ├── InputDonation.js
    │   │   │   ├── InputGroup.js
    │   │   │   ├── jioMoney.png
    │   │   │   ├── Mobiquick.png
    │   │   │   ├── MPesa.png
    │   │   │   ├── NetBanking.png
    │   │   │   ├── OlaMoney.png
    │   │   │   ├── payhere.css
    │   │   │   ├── PayHere.js
    │   │   │   ├── paytm_wallet.png
    │   │   │   ├── PayZapp.png
    │   │   │   ├── pg_iframe.html
    │   │   │   ├── QR_Code.png
    │   │   │   ├── SBIwallet.png
    │   │   │   ├── UPI.png
    │   │   │   └── Wallet.png
    │   │   ├── layout
    │   │   │   ├── Checkout.js
    │   │   │   ├── DonationCheckout.js
    │   │   │   ├── DonationThanks.css
    │   │   │   ├── DonationThanks.js
    │   │   │   ├── Header.js
    │   │   │   └── ThankYou.png
    │   │   ├── member-attendee-icon.png
    │   │   └── testPramodAgain.jpg
    │   ├── DonationPage
    │   │   ├── donation.css
    │   │   ├── DonationHead.js
    │   │   └── index.js
    │   ├── DropDownMenu
    │   │   └── index.js
    │   ├── Home
    │   │   ├── AboutUs.css
    │   │   ├── AboutUs.js
    │   │   ├── BBooks.js
    │   │   ├── Bgimage.js
    │   │   ├── BgimageOld.js
    │   │   ├── book.css
    │   │   ├── bookguidlines.css
    │   │   ├── bookguidlines.js
    │   │   ├── Book.js
    │   │   ├── books.css
    │   │   ├── Books.js
    │   │   ├── booksOld.css
    │   │   ├── BooksOld.js
    │   │   ├── BOY404.png
    │   │   ├── brain.jpg
    │   │   ├── category.css
    │   │   ├── Category.js
    │   │   ├── ChangeAddress.css
    │   │   ├── ChangeAddress.js
    │   │   ├── DataItem.js
    │   │   ├── Data.js
    │   │   ├── DonarAccDonarReq.css
    │   │   ├── DonarAccDonarReq.js
    │   │   ├── donorassurance.png
    │   │   ├── error404.css
    │   │   ├── Error404.js
    │   │   ├── error.png
    │   │   ├── faq.css
    │   │   ├── faq.js
    │   │   ├── footer.css
    │   │   ├── Footer.js
    │   │   ├── GBook.js
    │   │   ├── GetBooks.js
    │   │   ├── GIRL404.png
    │   │   ├── header.css
    │   │   ├── Header.js
    │   │   ├── home.css
    │   │   ├── Home.js
    │   │   ├── images
    │   │   │   ├── add.jfif
    │   │   │   ├── Aramex.png
    │   │   │   ├── banner.jpg
    │   │   │   ├── bestCollectionbooks.png
    │   │   │   ├── BestGiftForYourChildIcon.png
    │   │   │   ├── categoriesicon.png
    │   │   │   ├── Compititiveexams.png
    │   │   │   ├── delhivery.png
    │   │   │   ├── Deliveryicon.png
    │   │   │   ├── del.png
    │   │   │   ├── Donatebookslogo.png
    │   │   │   ├── fb.png
    │   │   │   ├── FedexIcon.png
    │   │   │   ├── footerPaymentGatewayIcon.png
    │   │   │   ├── footerRupay.png
    │   │   │   ├── footerTwitter.png
    │   │   │   ├── footerupi.png
    │   │   │   ├── footerVisa.png
    │   │   │   ├── footerwalleticon.png
    │   │   │   ├── GetBooks.png
    │   │   │   ├── google.png
    │   │   │   ├── Headercart.png
    │   │   │   ├── HeaderDonateBook.png
    │   │   │   ├── HomeBgImage.jpg
    │   │   │   ├── HomepageMostLovedBookBox.png
    │   │   │   ├── HomePageNCERTBanner.jpg
    │   │   │   ├── HomePageSiderBanner2.jpg
    │   │   │   ├── HomePageSliderBanner1.jpg
    │   │   │   ├── img.jpg
    │   │   │   ├── instagram.png
    │   │   │   ├── loc.png
    │   │   │   ├── LogesticPartnerIcon.png
    │   │   │   ├── loginsignUp.png
    │   │   │   ├── Mastercard.png
    │   │   │   ├── mobilencert.jpg
    │   │   │   ├── MyPustakLogo.png
    │   │   │   ├── mypustaknewlogo1.jpg
    │   │   │   ├── mypustaknewlogo.png
    │   │   │   ├── NetBanking.png
    │   │   │   ├── ourlinkIcon.png
    │   │   │   ├── ourStoryIcon.png
    │   │   │   ├── Prouddonors.png
    │   │   │   ├── set_elsearch_donor.py
    │   │   │   ├── SliderLeftArrow.png
    │   │   │   ├── SliderRightArrow.png
    │   │   │   └── Viswaserpostmortem.png
    │   │   ├── img.jpg
    │   │   ├── login.css
    │   │   ├── mobilecategory.css
    │   │   ├── mobilecategory.js
    │   │   ├── MyBooks.js
    │   │   ├── NewSearch.js
    │   │   ├── order.css
    │   │   ├── Order.js
    │   │   ├── orderpopup.js
    │   │   ├── PaytoConvert.js
    │   │   ├── Plogin.css
    │   │   ├── Popcat.css
    │   │   ├── Popupcategories.js
    │   │   ├── Pramodhome.css
    │   │   ├── PreGBook.js
    │   │   ├── privacypolicy.css
    │   │   ├── privacypolicy.js
    │   │   ├── PUserLogin.js
    │   │   ├── PUserSignup.js
    │   │   ├── qualityassurance.css
    │   │   ├── qualityassurance.js
    │   │   ├── Qualitybeforeshipment.png
    │   │   ├── Qualitycontrolteam.png
    │   │   ├── Qualitypacking.png
    │   │   ├── removed_home.css
    │   │   ├── resetPassword.css
    │   │   ├── ResetPassword.js
    │   │   ├── sale.jpg
    │   │   ├── SBook.js
    │   │   ├── Search.js
    │   │   ├── SearchOld.js
    │   │   ├── Slider.js
    │   │   ├── SliderOld.js
    │   │   ├── termsandcondition.css
    │   │   ├── termsandcondition.js
    │   │   ├── TestBooks.js
    │   │   ├── TestSearch.js
    │   │   ├── userLogin.css
    │   │   ├── UserLogin.js
    │   │   └── UserSignup.js
    │   ├── HomePage
    │   │   ├── form
    │   │   │   ├── DonationHomePagetopicon.png
    │   │   │   ├── DONATIONPageIMAGE1.jpg
    │   │   │   ├── form.css
    │   │   │   ├── Form.js
    │   │   │   ├── Input.js
    │   │   │   ├── Login.css
    │   │   │   ├── Login.js
    │   │   │   ├── ProudDonar.js
    │   │   │   ├── prouddonors.css
    │   │   │   ├── Signup.css
    │   │   │   └── Signup.js
    │   │   └── static
    │   │       ├── children.png
    │   │       ├── formfill.png
    │   │       ├── imgchild.jpg
    │   │       ├── OldStatic.css
    │   │       ├── OldStatic.js
    │   │       ├── pack_book.png
    │   │       ├── proud_back.jpg
    │   │       ├── Static.css
    │   │       └── Static.js
    │   ├── mainFooter.css
    │   ├── MainFooter.js
    │   ├── MainHeader.js
    │   ├── MainHeaderOld.js
    │   ├── Mobile
    │   │   └── SignInUp.js
    │   ├── mobimages
    │   │   ├── 10.png
    │   │   ├── 11.png
    │   │   ├── 12.png
    │   │   ├── 1.png
    │   │   ├── 2.png
    │   │   ├── 3.png
    │   │   ├── 4.png
    │   │   ├── 5.png
    │   │   ├── 6.png
    │   │   ├── 7.png
    │   │   ├── 8.png
    │   │   ├── 9.png
    │   │   ├── action.png
    │   │   ├── activity.png
    │   │   ├── aero.png
    │   │   ├── aieee.png
    │   │   ├── astro.png
    │   │   ├── ayur.png
    │   │   ├── banking.png
    │   │   ├── BA.png
    │   │   ├── bba.png
    │   │   ├── BCA.png
    │   │   ├── bcom.png
    │   │   ├── biography.png
    │   │   ├── bio.png
    │   │   ├── BSC.png
    │   │   ├── busi.png
    │   │   ├── cat.png
    │   │   ├── chem.png
    │   │   ├── children.png
    │   │   ├── ChildrensLiterature.png
    │   │   ├── civil.png
    │   │   ├── classno.png
    │   │   ├── coffeetable.png
    │   │   ├── comic.png
    │   │   ├── competitive.png
    │   │   ├── comp.png
    │   │   ├── computer.png
    │   │   ├── cookbook.png
    │   │   ├── cothers.png
    │   │   ├── dental.png
    │   │   ├── dic.png
    │   │   ├── dictionary.png
    │   │   ├── disney.png
    │   │   ├── drama.png
    │   │   ├── electrical.png
    │   │   ├── electronics.png
    │   │   ├── engg.png
    │   │   ├── engmed.png
    │   │   ├── entertainment.png
    │   │   ├── ETE.png
    │   │   ├── ETH.png
    │   │   ├── fictionicon.png
    │   │   ├── fiction.png
    │   │   ├── final
    │   │   │   ├── ACTIVITY BOOKS.png
    │   │   │   ├── astrology books copy.png
    │   │   │   ├── biography.png
    │   │   │   ├── BIO TECHNOLOGY copy.png
    │   │   │   ├── chemistry.png
    │   │   │   ├── CHILDren books.png
    │   │   │   ├── ChildrensLiterature.png
    │   │   │   ├── coffee table copy.png
    │   │   │   ├── coffeetable.png
    │   │   │   ├── comicbook.png
    │   │   │   ├── dictionary.png
    │   │   │   ├── drama books.png
    │   │   │   ├── DYSNYP copy.png
    │   │   │   ├── english to hindi.jpg
    │   │   │   ├── entertainment.png
    │   │   │   ├── geko.png
    │   │   │   ├── gmat.png
    │   │   │   ├── govt job.png
    │   │   │   ├── govt-jobs copy.png
    │   │   │   ├── gre.png
    │   │   │   ├── health books.png
    │   │   │   ├── history.png
    │   │   │   ├── horror.png
    │   │   │   ├── international exam copy.png
    │   │   │   ├── literary.png
    │   │   │   ├── medical BOOKS.png
    │   │   │   ├── non fiction copy.png
    │   │   │   ├── non fiction.png
    │   │   │   ├── pet.png
    │   │   │   ├── picture books.png
    │   │   │   ├── p&s.png
    │   │   │   ├── railway copy.png
    │   │   │   ├── sat.png
    │   │   │   ├── scfrict.png
    │   │   │   ├── shortstories.png
    │   │   │   ├── sports.png
    │   │   │   ├── SSC copy.png
    │   │   │   ├── tavel.png
    │   │   │   ├── teaching related.png
    │   │   │   ├── teen.png
    │   │   │   └── upsc copy.png
    │   │   ├── finance.png
    │   │   ├── Foreign.png
    │   │   ├── gate.png
    │   │   ├── geko.png
    │   │   ├── GK.png
    │   │   ├── gmat.png
    │   │   ├── govt.png
    │   │   ├── gre.png
    │   │   ├── health.png
    │   │   ├── history.png
    │   │   ├── hist.png
    │   │   ├── holy.png
    │   │   ├── homeicon.png
    │   │   ├── horror.png
    │   │   ├── house.png
    │   │   ├── HTE.png
    │   │   ├── humor.png
    │   │   ├── iit.png
    │   │   ├── international.png
    │   │   ├── KG.png
    │   │   ├── knowledge.png
    │   │   ├── LAW.png
    │   │   ├── literary.png
    │   │   ├── Logo and Icons
    │   │   │   ├── Category (CE1) Engineering  Medical
    │   │   │   │   ├── Category (CE1) Engineering & Medical.psd
    │   │   │   │   ├── -e-AIEEE.png
    │   │   │   │   ├── -e-GATE.png
    │   │   │   │   ├── -e-IIT.png
    │   │   │   │   ├── -e-med.png
    │   │   │   │   ├── -e-others.png
    │   │   │   │   └── -e-state level.png
    │   │   │   ├── Category (CE2) Government Jobs
    │   │   │   │   ├── banking.png
    │   │   │   │   ├── Category (CE2) Government Jobs.psd
    │   │   │   │   ├── others.png
    │   │   │   │   ├── railway.png
    │   │   │   │   ├── SSC.png
    │   │   │   │   ├── teaching.png
    │   │   │   │   └── UPSC.png
    │   │   │   ├── Category (CE3) International Exams
    │   │   │   ├── Category (CE4) School Level
    │   │   │   │   ├── Category (CE4) School Level.psd
    │   │   │   │   ├── -e-Filters.png
    │   │   │   │   ├── -e-NTSE.png
    │   │   │   │   ├── -e-olympaid.png
    │   │   │   │   ├── -e-others.png
    │   │   │   │   ├── -e-sainik school.png
    │   │   │   │   └── -e-school.png
    │   │   │   ├── Category (Competitive Exams) Icons
    │   │   │   │   ├── Category (Competitive Exams).png
    │   │   │   │   ├── cat.png
    │   │   │   │   ├── eng med.png
    │   │   │   │   ├── GK.png
    │   │   │   │   ├── Government  Jobs.png
    │   │   │   │   ├── INTERNATIONAL.png
    │   │   │   │   └── school level.png
    │   │   │   ├── Category (FB1) Fiction
    │   │   │   │   ├── Category (FB1) Fiction.psd
    │   │   │   │   ├── comic.png
    │   │   │   │   ├── drama.png
    │   │   │   │   ├── horror.png
    │   │   │   │   └── humor.png
    │   │   │   ├── Category (FB2) Non Fiction
    │   │   │   │   ├── astro.png
    │   │   │   │   ├── busi.png
    │   │   │   │   ├── Category (FB2) Non Fiction.psd
    │   │   │   │   ├── health.png
    │   │   │   │   └── hist.png
    │   │   │   ├── Category (Fiction Books)
    │   │   │   │   ├── Category (Fiction Books).png
    │   │   │   │   ├── Category (Fiction Books).psd
    │   │   │   │   ├── FICTION.png
    │   │   │   │   ├── non fic.png
    │   │   │   │   ├── others.png
    │   │   │   │   ├── religion.png
    │   │   │   │   └── self help.png
    │   │   │   ├── Category (SB1) Children Books
    │   │   │   │   ├── Category (CE4) School Level.psd
    │   │   │   │   ├── -e-Filters.png
    │   │   │   │   ├── -e-NTSE.png
    │   │   │   │   ├── -e-olympaid.png
    │   │   │   │   ├── -e-others.png
    │   │   │   │   ├── -e-sainik school.png
    │   │   │   │   └── -e-school.png
    │   │   │   ├── Category (SB2) Classes
    │   │   │   │   ├── Category (SB2) Classes.png
    │   │   │   │   ├── Category (SB2) Classes.psd
    │   │   │   │   ├── -e-10.png
    │   │   │   │   ├── -e-11.png
    │   │   │   │   ├── -e-12.png
    │   │   │   │   ├── -e-1.png
    │   │   │   │   ├── -e-2.png
    │   │   │   │   ├── -e-3.png
    │   │   │   │   ├── -e-4.png
    │   │   │   │   ├── -e-5.png
    │   │   │   │   ├── -e-6.png
    │   │   │   │   ├── -e-7.png
    │   │   │   │   ├── -e-8.png
    │   │   │   │   └── -e-9.png
    │   │   │   ├── Category (SB3) Dictionary Level
    │   │   │   │   ├── Category (SB3) Dictionary Level.png
    │   │   │   │   ├── Category (SB3) Dictionary Level.psd
    │   │   │   │   ├── ETE.png
    │   │   │   │   ├── ETH.png
    │   │   │   │   ├── Foreign.png
    │   │   │   │   ├── HTE.png
    │   │   │   │   └── subjectwise.png
    │   │   │   ├── Category (SB4) NCERT
    │   │   │   │   ├── Category (SB4) NCERT.png
    │   │   │   │   ├── Category (SB4) NCERT.psd
    │   │   │   │   ├── -e-N10.png
    │   │   │   │   ├── -e-N11.png
    │   │   │   │   ├── -e-N12.png
    │   │   │   │   ├── -e-N6.png
    │   │   │   │   ├── -e-N7.png
    │   │   │   │   ├── -e-N8.png
    │   │   │   │   └── -e-N9.png
    │   │   │   ├── Category (School Books)
    │   │   │   │   ├── Category (School Books).png
    │   │   │   │   ├── children.png
    │   │   │   │   ├── class.png
    │   │   │   │   ├── dic.png
    │   │   │   │   └── NCERT.png
    │   │   │   ├── Category (UB1) Engineering
    │   │   │   │   ├── aero.png
    │   │   │   │   ├── bio.png
    │   │   │   │   ├── Category (UB1) Engineering.psd
    │   │   │   │   ├── chem.png
    │   │   │   │   ├── civil.png
    │   │   │   │   ├── comp.png
    │   │   │   │   ├── electrical.png
    │   │   │   │   ├── electronics.png
    │   │   │   │   ├── marine.png
    │   │   │   │   ├── mechanical.png
    │   │   │   │   └── ubother.png
    │   │   │   ├── Category (UB2) Medical
    │   │   │   │   ├── Category (UB2) Medical.psd
    │   │   │   │   ├── -e-ayur.png
    │   │   │   │   ├── -e-dental.png
    │   │   │   │   ├── -e-Filters.png
    │   │   │   │   ├── -e-mbbs.png
    │   │   │   │   ├── -e-others.png
    │   │   │   │   ├── -e-PG.png
    │   │   │   │   └── -e-pharm.png
    │   │   │   ├── Category (UB3) Science Arts
    │   │   │   │   ├── Category (UB3) Science & Arts.psd
    │   │   │   │   ├── -e-BA.png
    │   │   │   │   ├── -e-BCA.png
    │   │   │   │   ├── -e-BSC.png
    │   │   │   │   ├── -e-MA.png
    │   │   │   │   ├── -e-MCA.png
    │   │   │   │   └── -e-MSC.png
    │   │   │   ├── Category (UB4) Others
    │   │   │   │   ├── Category (UB4) Others.psd
    │   │   │   │   ├── -e-bba.png
    │   │   │   │   ├── -e-bcom.png
    │   │   │   │   ├── -e-LAW.png
    │   │   │   │   ├── -e-MBA.png
    │   │   │   │   ├── -e-Mcom.png
    │   │   │   │   ├── -e-others.png
    │   │   │   │   └── -e-phd.png
    │   │   │   ├── Category (University Books)
    │   │   │   │   ├── Category (University Books).png
    │   │   │   │   ├── engg.png
    │   │   │   │   ├── finance.png
    │   │   │   │   ├── medical.png
    │   │   │   │   ├── others.png
    │   │   │   │   └── sci.png
    │   │   │   ├── Donatinon Page (3)
    │   │   │   │   ├── Donatinon Page (3) .png
    │   │   │   │   ├── Donatinon Page (3).psd
    │   │   │   │   └── steps.png
    │   │   │   ├── Donation Page
    │   │   │   │   ├── BANNER.png
    │   │   │   │   ├── Donation Page .png
    │   │   │   │   ├── Donation Page.psd
    │   │   │   │   └── steps.png
    │   │   │   ├── Donation Page (2)  (Form)
    │   │   │   │   ├── arrow down.png
    │   │   │   │   ├── Books image.png
    │   │   │   │   ├── Donation Page (2)  (Form) .png
    │   │   │   │   ├── Donation Page (2)  (Form).psd
    │   │   │   │   ├── file upload.png
    │   │   │   │   ├── Pickup date.png
    │   │   │   │   └── steps.png
    │   │   │   ├── Donation Status
    │   │   │   │   ├── dummy-profile-pic.png
    │   │   │   │   └── -e-Layer 3.png
    │   │   │   └── Home Page
    │   │   │       ├── competitve.png
    │   │   │       ├── Donate books.png
    │   │   │       ├── -e-Home Icon.png
    │   │   │       ├── -e-mypustak logo.png
    │   │   │       ├── -e-Search Icon.png
    │   │   │       ├── fiction.png
    │   │   │       ├── get books.png
    │   │   │       ├── Home Page.psd
    │   │   │       ├── school.png
    │   │   │       └── university.png
    │   │   ├── MA.png
    │   │   ├── marine.png
    │   │   ├── MBA.png
    │   │   ├── mbbs.png
    │   │   ├── MCA.png
    │   │   ├── Mcom.png
    │   │   ├── mechanical.png
    │   │   ├── medical.png
    │   │   ├── med.png
    │   │   ├── mothers.png
    │   │   ├── MSC.png
    │   │   ├── mystery.png
    │   │   ├── N10.png
    │   │   ├── N11.png
    │   │   ├── N12.png
    │   │   ├── N6.png
    │   │   ├── N7.png
    │   │   ├── N8.png
    │   │   ├── N9.png
    │   │   ├── NCERT.png
    │   │   ├── New folder
    │   │   │   ├── action.png
    │   │   │   ├── comp.png
    │   │   │   ├── cookbook.png
    │   │   │   ├── holy.png
    │   │   │   ├── house.png
    │   │   │   ├── KG.png
    │   │   │   ├── knowledge.png
    │   │   │   ├── mystery.png
    │   │   │   ├── PHILOSOPHY.png
    │   │   │   ├── photography.png
    │   │   │   ├── religionbook.png
    │   │   │   ├── romance.png
    │   │   │   └── SPIRITUALITY.png
    │   │   ├── nonfic.png
    │   │   ├── ntse.png
    │   │   ├── olympiad.png
    │   │   ├── others1.png
    │   │   ├── others.png
    │   │   ├── pet.png
    │   │   ├── PG.png
    │   │   ├── pharm.png
    │   │   ├── phd.png
    │   │   ├── PHILOSOPHY.png
    │   │   ├── photography.png
    │   │   ├── picbook.png
    │   │   ├── p&s.png
    │   │   ├── railway.png
    │   │   ├── religionbook.png
    │   │   ├── religion.png
    │   │   ├── romance.png
    │   │   ├── sainikschool.png
    │   │   ├── sat.png
    │   │   ├── scfrict.png
    │   │   ├── schoollevel.png
    │   │   ├── school.png
    │   │   ├── sci.png
    │   │   ├── searchicon.png
    │   │   ├── selfhelp.png
    │   │   ├── shortstories.png
    │   │   ├── sothers.png
    │   │   ├── SPIRITUALITY.png
    │   │   ├── sports.png
    │   │   ├── sschool.png
    │   │   ├── SSC.png
    │   │   ├── statelevel.png
    │   │   ├── subjectwise.png
    │   │   ├── teaching.png
    │   │   ├── teen.png
    │   │   ├── travel.png
    │   │   ├── ubother.png
    │   │   ├── university.png
    │   │   ├── uoothers.png
    │   │   └── UPSC.png
    │   ├── mypassbook.css
    │   ├── mypustak icon new.png
    │   ├── Old_contact.css
    │   ├── Old_Contact.js
    │   ├── OldPramodwallet.css
    │   ├── OrderManagement
    │   │   ├── index.js
    │   │   └── OrderManagement.css
    │   ├── OrderPage
    │   │   ├── donation.css
    │   │   ├── index.js
    │   │   ├── Olindex.js
    │   │   └── OrderHead.js
    │   ├── Passbook.js
    │   ├── PayPalButton.js
    │   ├── Popupcart.css
    │   ├── PramodOld_MainHeader.js
    │   ├── Proceedpay.css
    │   ├── ProceedToPay.js
    │   ├── product
    │   │   ├── newProduct.css
    │   │   ├── Old_newProduct.css
    │   │   ├── Product_Images
    │   │   │   └── del.png
    │   │   ├── Product.js
    │   │   ├── TASK
    │   │   ├── wishlist.css
    │   │   └── Wishlist.js
    │   ├── UpdateTrackingAndBarcode
    │   │   ├── index.js
    │   │   └── UpdateTrackingAndBarcode.css
    │   ├── wallet.css
    │   ├── walleticon.png
    │   ├── Wallet.js
    │   ├── WalletPage
    │   │   ├── donation.css
    │   │   ├── index.js
    │   │   └── WalletHead.js
    │   ├── WalletProceedToPay.js
    │   └── workimage background.jpg
    ├── config
    │   ├── dev.js
    │   ├── index.js
    │   └── prod.js
    ├── fonts
    │   └── Tahoma.ttf
    ├── index.css
    ├── index.js
    ├── Pramod_change.txt
    ├── reducers
    │   ├── accountReducer.js
    │   ├── addressReducers.js
    │   ├── backendBookInventoryReducer.js
    │   ├── backendConfirmOrderReducer.js
    │   ├── backendDonationReducer.js
    │   ├── backendOrderReducer.js
    │   ├── backendWalletReducer.js
    │   ├── backofficedonationtrackinggetReducer.js
    │   ├── backofficeorderdetailsReducer.js
    │   ├── backofficeWalletUpdateReducers.js
    │   ├── cartReducers.js
    │   ├── compExamReducers.js
    │   ├── dataentrysalebydaterangeReducers.js
    │   ├── donationReducer.js
    │   ├── faqReducer.js
    │   ├── frictionReducers.js
    │   ├── getProductReducers.js
    │   ├── homeReducers.js
    │   ├── index.js
    │   ├── orderReducer.js
    │   ├── passbookReducer.js
    │   ├── ProuddonarReducer.js
    │   ├── schoolBookReducers.js
    │   ├── seodataReducer.js
    │   ├── totalsalefilterReducers.js
    │   ├── UniversityBookReducers.js
    │   ├── walletReducer.js
    │   └── wishlistReducer.js
    ├── reducers.zip
    ├── router.js
    ├── serviceWorker.js
    ├── store.js
    ├── templates
    │   └── test.html
    ├── ToDO
    └── util
        └── helpers.js

#### There are Total 30 pages
1./login->component(SignInUp)
2./donate-books->component(Form)
3./pages/terms-conditions->component(TermsCondtion)
4./wallet/passbook/->component(Passbook)
5./donor/donor_donation_request->component(DonarAccDonarReq)
