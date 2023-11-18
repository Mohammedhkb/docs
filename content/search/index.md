
// الخوارزمية لسرد أسماء لغات البرنامج المفضلة

// إنشاء مصفوفة لتخزين الأسماء
let languages = [];

// دالة لإضافة لغة إلى القائمة
function addLanguage(language) {
  if (languages.includes(language)) {
    console.log("لقد أدخلت اللغة من قبل.");
  } else {
    languages.push(language);
    console.log("تمت إضافة اللغة بنجاح.");
  }
}

// إضافة 5 لغات بالأولوية
addLanguage("JavaScript");
addLanguage("Python");
addLanguage("Swift");
addLanguage("Java");
addLanguage("Python");
