# GP1-Code

Jack Mowat
S1429209
Computer Games Design
I confirm that the code contained in this file (other than that provided or authorised)
is all my own work and has not been submitted elsewhere in fulfilment of this or any other award.
JACK

The following is a list of the code I have used, created or adjusted for my GP1 submission.

main:

LPCSTR texturesToUse[] = { "Images\\cowboy-clip-art.png", "Images\\cowboy-clip-art.png", "Images\\cowboy-clip-art.png", "Images\\cowboy-clip-art.png", "Images\\bullet.png" };

textureBkgd.createTexture("Images\\WildWestGhostTown.png");

rocketTxt.createTexture("Images\\crosshair-th.png");

Rocket:

if (m_InputMgr->isKeyDown(VK_RIGHT))
	{
		spriteRotation = + 90;
	}
if (m_InputMgr->isKeyDown(VK_LEFT))
	{
		spriteRotation = 0;
	}
if (m_InputMgr->isKeyDown(VK_UP))
	{
		spriteTranslation = (glm::vec2(4.0f, 4.0f));
	}
if (m_InputMgr->isKeyDown(VK_DOWN))
	{
		spriteTranslation = -(glm::vec2(4.0f, 4.0f));
	}

Bullet:

bulletVelocity *= 0.0;

END
