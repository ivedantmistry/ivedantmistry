[![An image of @vedantmistryy's Holopin badges, which is a link to view their full Holopin profile](https://holopin.me/vedantmistryy)](https://holopin.io/@vedantmistryy)
const githubProfile = {
    username: "YourUsername",
    name: "Your Full Name",
    bio: "Passionate developer who loves coding!",
    repositories: 20,
    followers: 500,
    following: 150,
    location: "Your City, Country",
    website: "https://yourwebsite.com",
    avatarUrl: "https://youravatarurl.com",
    topLanguages: [
        { language: "JavaScript", percentage: 40 },
        { language: "Python", percentage: 25 },
        { language: "HTML/CSS", percentage: 20 },
        // Add more languages as needed
    ],
    recentRepositories: [
        { name: "Project A", description: "A cool project.", stars: 100 },
        { name: "Project B", description: "Another awesome project.", stars: 200 },
        // Add more repositories
    ],
    contributions: [
        { repository: "Open Source Repo 1", count: 10 },
        { repository: "Open Source Repo 2", count: 5 },
        // Add more contributions
    ],
};

// Accessing and displaying profile details
console.log(`GitHub Username: ${githubProfile.username}`);
console.log(`Name: ${githubProfile.name}`);
console.log(`Bio: ${githubProfile.bio}`);
console.log(`Repositories: ${githubProfile.repositories}`);
console.log(`Followers: ${githubProfile.followers}`);
console.log(`Following: ${githubProfile.following}`);
console.log(`Location: ${githubProfile.location}`);
console.log(`Website: ${githubProfile.website}`);
console.log(`Avatar URL: ${githubProfile.avatarUrl}`);

// Displaying top programming languages
console.log("Top Programming Languages:");
githubProfile.topLanguages.forEach(language => {
    console.log(`${language.language}: ${language.percentage}%`);
});

// Displaying recent repositories
console.log("Recent Repositories:");
githubProfile.recentRepositories.forEach(repo => {
    console.log(`- ${repo.name}: ${repo.description} (Stars: ${repo.stars})`);
});

// Displaying contributions to open source projects
console.log("Contributions to Open Source:");
githubProfile.contributions.forEach(contribution => {
    console.log(`- ${contribution.count} contributions to ${contribution.repository}`);
});
