function dailyLog232() {
  const visitors = 1500;
  const signups = 185;
  const newUsers = 172;
  const verifiedUsers = 160;

  const conversionRate = (signups / visitors) * 100;
  const verificationRate = (verifiedUsers / signups) * 100;

  console.log("Daily Sign-up Report");
  console.log("--------------------");
  console.log(`Visitors: ${visitors}`);
  console.log(`New Sign-ups: ${signups}`);
  console.log(`New Users: ${newUsers}`);
  console.log(`Verified Users: ${verifiedUsers}`);
  console.log(`Conversion Rate: ${conversionRate.toFixed(2)}%`);
  console.log(`Verification Rate: ${verificationRate.toFixed(2)}%`);
}

dailyLog232();
